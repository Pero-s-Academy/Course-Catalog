# Course-Catalog Repository Enhancement Task

## Objective
Refine and organize the `Course-Catalog` repository at Pero's Academy, making it a comprehensive hub for educational materials across various domains such as Operating Systems, Programming Languages, Technology, and Vendor-specific courses.

## Task Breakdown

### 1. **Enhance Directory Structure**
Your first task is to structure the repository into clearly defined categories. Below is the hierarchy you need to implement:

```
Course-Catalog/
│
├── Operating-Systems/
│   ├── AIX/
│   ├── Android/
│   ├── Apple-OS/
│   ├── Fedora/
│   ├── HPUX/
│   ├── IBM-I/
│   ├── Kali/
│   ├── RedHat/
│   ├── SUSE/
│   ├── Windows/
│   └── z-OS/
│
├── Programming-Languages/
│   ├── C/
│   │   ├── Courses/
│   │   ├── Projects/
│   │   └── Resources/
│   ├── C++/
│   │   ├── Courses/
│   │   ├── Projects/
│   │   └── Resources/
│   ├── Go/
│   │   ├── Courses/
│   │   ├── Projects/
│   │   └── Resources/
│   ├── Java/
│   │   ├── Courses/
│   │   ├── Projects/
│   │   └── Resources/
│   ├── JavaScript/
│   │   ├── Courses/
│   │   ├── Projects/
│   │   └── Resources/
│   ├── Python/
│   │   ├── Courses/
│   │   ├── Projects/
│   │   └── Resources/
│   └── [Other Languages]/
│
├── Technology/
│   ├── Applications/
│   │   ├── Courses/
│   │   └── Resources/
│   ├── Cloud/
│   │   ├── Courses/
│   │   └── Resources/
│   ├── Development-Integration-DevOps-Automation/
│   │   ├── Courses/
│   │   └── Resources/
│   ├── Networks/
│   │   ├── Courses/
│   │   └── Resources/
│   ├── Security/
│   │   ├── Courses/
│   │   └── Resources/
│   └── Storage/
│       ├── Courses/
│       └── Resources/
│
└── Vendors/
    ├── Adobe/
    ├── AWS/
    ├── Checkpoint/
    ├── CISCO/
    ├── CompTIA/
    ├── Dell/
    ├── F5-Networks/
    ├── Fortinet/
    ├── GitHub/
    ├── Google/
    ├── HP/
    ├── IBM/
    ├── Juniper-Networks/
    ├── Lenovo/
    ├── Microsoft/
    ├── Nutanix/
    ├── Okta/
    ├── Oracle/
    ├── RedHat/
    ├── Salesforce/
    ├── SAP/
    ├── Symantec/
    └── VMware/
```

#### Step-by-Step Guide:
- **Navigate to the Repository**: Open a terminal or command prompt and navigate to your local `Course-Catalog` repository clone.
- **Create Directories**: Use the `mkdir` command for Linux/Mac or `New-Item` cmdlet for Windows PowerShell to create the directory structure as shown. Example for creating the `Operating-Systems` directories:
  ```bash
  mkdir -p Operating-Systems/{AIX,Android,Apple-OS,Fedora,HPUX,IBM-I,Kali,RedHat,SUSE,Windows,z-OS}
  ```
- **Push Changes**: After creating the directories, add them to your git staging area and commit:
  ```bash
  git add .
  git commit -m "Structured Operating Systems directories"
  git push origin main
  ```

### 2. **Initialize README Files**
Each directory and subdirectory should contain a `README.md` file that introduces the section and provides guidance on its contents.

#### Step-by-Step Guide:
- **Create README Files**: In each directory, create a `README.md` with an overview of the directory's purpose. Use a text editor or the `echo` command, for example:
  ```bash
  echo "# Operating Systems\nThis directory contains courses and resources related to various operating systems." > Operating-Systems/README.md
  ```
- **Content Suggestions**: For programming languages, include the language's history, key features, and application areas in the `README.md`.
- **Commit and Push**: Don't forget to commit your changes and push them to the repository after adding the README files.

### 3. **Sample Content Creation**
To guide future contributions, populate the `Courses`, `Projects`, and `Resources` subdirectories with sample markdown files.

#### Step-by-Step Guide:
- **Create Sample Files**: Add files like `sample-course-outline.md` in the `Courses` folder to serve as a template. You might include a basic course structure, objectives, and prerequisites.
  ```bash
  touch Programming-Languages/Python/Courses/sample-course-outline.md
  ```
- **Add Content**: Fill the sample files with placeholder content that indicates the expected structure and information. For instance, the `sample-course-outline.md` might contain headers for "Course Introduction", "Learning Outcomes", "Course Schedule", etc.
- **Commit and Push**: Regularly commit your changes to track progress and push them to the repository to make them available to others.

### 4. **Set Access Controls**
Configure the repository settings to manage contributor access, ensuring that content integrity is maintained.

#### Step-by-Step Guide:
- **GitHub Settings**: Go to the repository settings on GitHub, navigate to the "Manage Access" section, and invite team members as collaborators, assigning appropriate roles.
- **Branch Protection**: Consider setting up branch protection rules for the `main` branch to require pull request reviews before merging.

### 5. **Draft CONTRIBUTING.md**
Create a `CONTRIBUTING.md` file to outline how members can contribute to the repository, detailing the workflow, coding standards, and PR process.

#### Step-by-Step Guide:
- **Content Structure**: Divide the document into sections such as "How to Contribute", "Style Guide", "Commit Messages", and "Pull Request Process".
- **Examples and Templates**: Provide examples for good commit messages, PR descriptions, and code formatting guidelines.

## Deliverables

- A structured `Course-Catalog` repository with initialized `README.md` files and sample content.
- A comprehensive `CONTRIBUTING.md` file detailing contribution guidelines.

## Submission

Submit a link to the updated `Course-Catalog` repository, along with a document outlining the steps taken, challenges encountered, and solutions applied.

## Deadline

- Complete all tasks and submit by **16 February 2024, 17:00h**.

This task will test your ability to organize a large-scale repository, create clear and helpful documentation, and set guidelines for collaborative work.
