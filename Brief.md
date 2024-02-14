# Course-Catalog Repository Setup Task

## Objective
Enhance and structure the existing `Course-Catalog` repository at Pero's Academy to serve as a centralized hub for educational materials, covering Operating Systems, Programming Languages, Technology, and Vendor-specific content.

## Task Instructions

### Directory Structure
Organize the repository into the following main categories, each with specific subdirectories:

#### Operating Systems
Create subdirectories for various operating systems. Each OS directory should have its own `README.md` explaining its content focus.

- **Example**:
  ```plaintext
  mkdir -p Operating-Systems/{AIX,Android,Apple-OS,Fedora,HPUX,IBM-I,Kali,RedHat,SUSE,Windows,z-OS}
  ```

#### Programming Languages
For each programming language, set up `Courses`, `Projects`, and `Resources` subdirectories.

- **Example**:
  ```plaintext
  mkdir -p Programming-Languages/Python/{Courses,Projects,Resources}
  ```

#### Technology
Divide this category by technology topics like `Applications`, `Cloud`, etc., including `Courses` and `Resources` for each.

- **Example**:
  ```plaintext
  mkdir -p Technology/Cloud/{Courses,Resources}
  ```

#### Vendors
Create a directory for each major vendor. Consider adding a `README.md` in each to describe available resources or courses.

- **Example**:
  ```plaintext
  mkdir -p Vendors/{Adobe,AWS,Checkpoint}
  ```

### Content Creation

#### README Files
Populate each directory and subdirectory with a `README.md`. Provide an overview, purpose, and any relevant information for navigating the contents.

- **Guide**: Use Markdown for formatting. Include descriptive titles, concise descriptions, and links to subdirectories or external resources.

#### Sample Files
Introduce sample content files within `Courses`, `Projects`, and `Resources` to serve as templates.

- **Action**: Create files like `sample-course-outline.md`, `sample-project-description.md`, and `useful-links.md`.
- **Commit Message Example**: "Added sample course outline for Python courses."

### Access Control and Collaboration

Set appropriate permissions to manage who can contribute to the repository, ensuring content integrity and review.

- **Guide**: Utilize GitHub's [collaborator settings](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/managing-access-to-your-personal-repositories/inviting-collaborators-to-a-personal-repository) to add team members with specific roles.

### Branching and Workflow

Adopt a workflow that includes feature branches merging into a development branch (`develop`), which then merges into the main branch (`main`) after review.

- **Action**: Create a `develop` branch as a staging area for reviewing changes before they go live.
- **Commit Message Example**: "Merging feature/update-python-resources into develop."

### Contribution Guidelines

Draft a detailed `CONTRIBUTING.md` outlining the process for making contributions, including coding standards, naming conventions, and pull request (PR) guidelines.

- **Contents**: Include sections on how to fork the repo, create feature branches, submit PRs, and the review process.
- **Commit Message Example**: "Added CONTRIBUTING guidelines for repository contributors."

## Deliverables

- A well-structured `Course-Catalog` repository with initial READMEs and sample content.
- A `CONTRIBUTING.md` document that outlines the contribution process and guidelines.

## Submission

- Provide a link to the updated `Course-Catalog` repository.
- Include a brief report detailing the setup process, any challenges encountered, and solutions implemented.

## Deadline

- All tasks must be completed and submitted by **16 February 2024, 17:00h**.

This task is designed to assess your ability to organize and manage educational content in a collaborative environment, ensuring ease of access and clarity for all potential contributors and users of the `Course-Catalog` repository.
