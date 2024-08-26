#git_assignment
# Git Assignment - tazeenq

    a. What is an issue?
GitHub Issues are a tool to communicate decisions, ideas, and problems specific to a project. They are used in place of email or SLack - communication via Issues is project specific though. Issues are available on GitHub when they are open or closed, and they are accessible to all project collaborators.

    b. What is a pull request?

git pull automatically fetches and merges a remote project branch to our current branch (in other words: pulls changes from remote into your local directory). It is a good practice to pull before every work session, to stay updated on all changed made by others working on the same project. We can create a pull request if we are collaborating with others and want our changes merged to the original repo.

    c. Describe the steps to open a pull request?

Step 1: Go to the project repo in Github
Step 2: Click on the Pull requests tab
Step 3: Click on the 'New pull Request' button on the page
Step 4: Select your base repo and comparison branch
Step 5: Click 'Create Pull Request'
Step 6: After reviewing all the changes made to the file, and leaving comments (optional), click the 'Create pull request' button at the end of the page again.

Alternatively, we can also pull using CLI by using the '$ git pull' command. 

    d. Describe the steps to add a collaborator to a repository (share write permissions)
Step 1: Go to the project repo in Github
Step 2: Click on Settings
Step 3: Go to 'Collaborators' under 'Access' in the left hand pane and click on 'Add people'. We can search a collaborator by their username, full name, or email. 
Step 4: If the Github account is for an organization: Once we find a collaborator in the dropdown list, we can choose their role. Select 'Write' to grant the individual permission to view and edit the project. Then click 'Invite'.
Alternatively,
Step 4: If the repository is in a personal account (or a personal repository): Once we find a collaborator in the dropdown list, we can select them and click 'Add <Collaborator's Name> to this repository'. For personal repositories, collaborators can read (pull) the contents and write (push) changes to the repository.

    e. What is the difference between git and GitHub?

Git is version control system that tracks changes in files in a local environment (on your personal computer), while GitHub is a cloud-based platform where we can store, share, and collaborate with others to write code. Git is maintained by Linux and Microsoft owns Github.
    
    f. What does git diff do?

git diff compares what is in our working directory to what is in our staging area. If we've made changes to our file without running 'git add', we will see the comparison between the two.

    g. What is the main branch?

In Git, main branch is the default branch in a repo. It is also called 'master'. 

    h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

No, we should not push our changes directly into the main branch. Branching allows us to diverge from the main line to do work without accidentally messing with the main line. This helps with testing without making any accidental changes to the working branch.
