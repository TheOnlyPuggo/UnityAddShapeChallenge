The challenge is to create a branch of the 'main' repository, open this branch locally on your computer in unity, add one of the shape sprites to the SampleScene, and then push your changes to the 'test-branch'.
The idea is that for everyone participating in the game jam group has their unity project additions in one repository, which is a skill we'll need if we want to work on one unity project together.
Also make sure to delete the branch you created once you have merged with 'test-branch'.

How to do this:
1. Make sure to have Github Desktop installed, which will allow you to use git commands without having to use a terminal.
2. Create a new unity project, make sure it is a 'Universal 2D' project, which is what this repo is using. Also make sure you know where in your file system you are creating this project.
3. In github desktop, click 'Clone a repository from the Internet' and use the url of this repo to clone it. Where you clone it doesn't matter, as we will be dragging and dropping the contents of the cloned folder into a different location.
4. Once the Unity project is done being created and the repository is cloned, you want to drag and drop the contents of the repository clone folder into your unity project. **IMPORTANT**: The contents of the repository clone folder will include a .git file, which by default file explorer doesn't show because of the '.' prefix. You can look up how to show hidden files specific to your os, however for windows file explorer you want to click View->Show->Hidden items. Once you have dragged and dropped all the files from the repo folder to the unity project folder, you should get a prompt saying if you want to replace files in the destination, click 'yes' or whatever equivalent button you have.
5. Because the repository git files were moved, github desktop will ask you to 
