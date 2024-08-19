# TestGithub
Learn GitHub Repository Sharing

Collaborate using various functions
- Fork
- Branch
- Merge
- Fetch
- Pull Request

Steps to duplicate code/files from old repository to new
* git clone --bare https://github.com/exampleuser/old-repository.git

* cd old-repository.git
* git push --mirror https://github.com/exampleuser/new-repository.git

* cd ..
* rm -rf old-repository.git
