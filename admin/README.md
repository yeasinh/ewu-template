# University Website CMS& DMS admin panel

**East West Admin** 

# Tehcnology Used
  Tailwind CSS, Next.js etc

# Node Version
  20.x.x Lts

## Installation Process
 # Yarn install  
    npm install --global yarn
 #  Dependency installation
     yarn
 # Project Build
    yarn dev

 # Git Branching Policy

This document outlines the branching strategy and naming conventions for our Git workflow. The goal is to maintain a clean and organized repository while ensuring efficient collaboration among team members.

## Branch Prefixes

To standardize branch names, use the following prefixes based on the purpose of the branch:

### 1. `arch/` (Architecture)
- **Purpose**: For changes related to project architecture, such as restructuring directories, updating build systems, or modifying deployment configurations.
- **Examples**:
  - `arch/update-build-system`
  - `arch/restructure-modules`

### 2. `feat/` (Feature)
- **Purpose**: For new features or enhancements to existing functionality.
- **Examples**:
  - `feat/user-authentication`
  - `feat/add-dark-mode`

### 3. `fix/` (Bug Fix)
- **Purpose**: For fixing bugs or addressing issues in the code.
- **Examples**:
  - `fix/login-redirect`
  - `fix/api-response-error`

## General Guidelines

1. **Branch Naming**:
   - Use descriptive names that clearly convey the purpose of the branch.
   - Avoid overly long or vague names.
   
2. **Commit Messages**:
   - Write clear and concise commit messages that explain the changes.
   - Use the imperative mood (e.g., "feat: Add user authentication").

3. **Pull Requests (PRs)**:
   - Ensure all branches go through a pull request before being merged.
   - Review the changes thoroughly and ensure they meet project standards.

4. **Branch Lifespan**:
   - Delete branches after they have been merged to keep the repository clean.
   
## Example Workflow

1. **Create a Branch**:
   ```bash
   git checkout -b feat/add-user-profile
   ```

2. **Work on the Branch**:
   - Make changes, commit them regularly, and push the branch to the remote repository.
   ```bash
   git push origin feat/add-user-profile
   ```

3. **Create a Pull Request**:
   - Open a pull request on the repository, linking to any relevant issue or ticket.

4. **Code Review and Merge**:
   - After approval, merge the branch into the main branch (e.g., `main` or `develop`).

By adhering to this branching policy, we can ensure a streamlined and efficient development process. Happy coding!

