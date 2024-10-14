# COMP3104_Group51_Assignment
## Group Members
- **Leader:** Krishna Thakkar (101398578) - [GitHub](https://github.com/krishna0718)
- **Member 2:** Pratham bavlawala (101410156) - [GitHub](https://github.com/prathambavlawala)
- **Member 3:** Ishika Koshiya (101413772) - [GitHub](https://github.com/ishikakoshiya)
- **Member 3:** Nandani kevadiya (101413773) - [GitHub](https://github.com/nandani-kevadiya)

## Project Description
This project serves as the group assignment for the COMP3104 DevOps course. The focus is on collaborative Git workflows,
implementing effective branching strategies, and integrating a CI/CD pipeline using GitHub Actions. 
Each team member contributes through individual branches and the project is developed following continuous integration best practices.
## Setup Instructions
1. Clone the repository.
`git clone https://github.com/krishna0718/COMP3104_Group51_Assignment.git`
2. Switch to your branch using `git checkout STUDENTID-Name`.
3. Install any dependencies as listed.
## CI/CD Pipeline
This project integrates continuous integration using GitHub Actions.
 The pipeline is defined in .github/workflows/ci.yml and is configured to run on all push events.
CI Pipeline Steps:
Run the Workflow: Automatically triggered by push events on any branch.
Checkout the Repository: Uses the GitHub checkout action to clone the repository.
Build and Test: Any necessary build and test steps are executed to ensure code quality.
To customize or check the workflow, refer to the ci.yml file located in the .github/workflows/ directory.
## Branching Strategy
Each group member follows a strict branching convention. The branch name format is:
STUDENTID-Name (e.g., 101398578-Krishna)
Each member pushes their work to their respective branches. 
Changes are merged into the main branch via Pull Requests (PR), ensuring code review and quality checks before the merge.
