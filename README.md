What do you understand by Git?
Git is a free open source version control system created by Linus Torvaldy. Git is distributed and every developer has the entire history of their code repository locally. It has an excellent support for branching, merging and rewriting history. It is the most widely used control version system today.

Define Version Control
Version control system, also known as source control, is a system that tracks and manages changes whenever we write new code or take further actions while writing our code. It is a convenient management tool which helps in fast product release. It helps development teams to work smarter and faster as a project gets bigger. It keeps track of every modification made in a specific kind of database. So if any mistake is made, developers can compare earlier versions of their code to help fix errors while maximising disruption of all team members.

Describe the process of committing a project to github repository.
Open github, click on profile, new repository, enter your desired repository name.
If you want your code to be private click 'private' or if you want it to be viewed by all click 'public'.
Tick 'add a readme file' if you want to add a read me file.
Tick 'gitignore' if you have files you do not want to push online
Tick 'choose a licence' to tell others what they can and can't do with your code
Make sure your folder name is the same as the one in your remote so as not to encounter errors when pushing your code.
Open your IDE eg vscode.
Create a file, go to terminal then enter the instructions below

echo "# sample" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/....
git push -u origin main
