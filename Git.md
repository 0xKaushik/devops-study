Git is a version control system that helps in managing the version of the software.
A VCS helps in storing multiple version of a software in a single repo 
It helps every developer have the entire copy of the code locally
Everyone shares code in a peer-to-peer approach
It's difficult for bigger groups/organisations to work simultaneously

## Github

Github is a remote-server for the source code management
It has the ability to handle large projects

| Git                                                  | Github                                           |
| ---------------------------------------------------- | ------------------------------------------------ |
| Git is a software tool                               | Github is a service                              |
| on Local system                                      | Hosted on the Web                                |
| Used to manage different versions of the source code | It is used to have a copy of the local repo code |
| CLI                                                  | GUI                                              |

---
### Git Architecture 

                            +------------------------+
                            |    Remote Repository    |
                            | (GitHub, GitLab, etc.)  |
                            +------------------------+
                                      ^
                                      |
                                 git push | git pull
                                      |
                            +------------------------+
                            |    Local Repository     |
                            |     (Git Directory)     |
                            +------------------------+
                                      ^
                                      |
                                 git commit
                                      |
                            +------------------------+
                            |     Staging Area        |
                            |  (Index, where files    |
                            |   are added with git add)|
                            +------------------------+
                                      ^
                                      |
                                 git add
                                      |
                            +------------------------+
                            |  Working Directory      |
                            | (Your project files)    |
                            +------------------------+


Forking -> Creating a copy of an Open-source project and creating a new project out of it

Cloning -> Creating an identical copy of the code

Collaborators -> Team members working together

Branching -> Create a separate version of the code to work on new features

Pull -> Being able to pull software from the remote server

Rebase -> Re-establish a new start on the project

