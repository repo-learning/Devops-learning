# Git Branching starategy

## What is Git?

Git is a DevOps tool used for source code management. It is a free and open-source version control system used to handle small to very large projects efficiently. Git is used to tracking changes in the source code, enabling multiple developers to work together on non-linear development.
## What is a branch?

A repository is your whole project (directories and files). A branch is a version of your repository, or in other words, an independent line of development. A repository can contain multiple branches, which means there are multiple versions of the repository.
Master is usually for active development. When the work is going on for a new feature or new release, you don’t want those changes on the already working and stable main code until the branch code is tested well and passed to merge on to the master.
1. **Master** – Stable code. Active development and small fixes on this.
1. **Feature branch** – Any new feature development will be on this branch. Tested well and merged back to Master. This will be deleted after the merge.
1. **Release branch** – Used to release the new feature code. Master+feature code will be created to new release branch. End to end testing of the application is done and deliver the code to the customer from this branch.
1. **Hotfix branch** – For any issues in production, a Hotfix branch will be created.
Any branch changes should be merged back to Master and it should be up to date.
