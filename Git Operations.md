Git important Keywords and Operations
-------------------------------------

-Commit: Commit holds the current state of the Repository.Every commit
object has a pointer to the parent commit object.From a given commit,you
cab traverse back by looking at the parent pointer to view the history
of the commit.

-Branches:Branches are used to create another line of development.By
default,Git has a **Master** branch,which is same as *trunk* in
subversion.

-Tags: Tags assigns a meaningful name with a specific version in the
repository.Tags are very similar to *Branches* but the difference is
that tags are immutable.It means tag is a branch,which no one intends to
modify.Once a tag is created for a particular commit,even if you create
a new commit,it will not be updated.Usually developers create tags for
product releases.

-Clone: Clone operation creates the *Instance of the repository*. It not
only checks out the working copy,but also mirrors the complete
repository.

-Pull: Pull operation copies the changes from a Remote repo. to the
local one.The Pull op.is used for synchronization between the two
repository instances.

    -Push: Push op. copies changes from a local repo. instance to a remote
          one.This is used to store the changes permently into the Git
          Repository.

     -HEAD: HEAD is a pointer,which always points to the latest commit
           in the branch.Whenever you make a commit,HEAD is updated
          with the latest commit.

     -Revision: Revision represents the version of the source code.
               Revisions in Git are represented by commits.

     -Pull Request:Pull requests are proposed changes to a repository
               submitted by a user and accepted or rejected by a 
                repository's collaborators.

     -Merge:Merging takes the changes from one branch(in the same
            repository or from a fork),and applies them into another.


     -Collaborator:A collaborator is a person with read & write access
              to a repository who has been invited to contribute by the 
            repository owner.
