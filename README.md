# Application for running study on children's inferences from generic language 
Animation for study examining children's inferences about unmentioned groups from generic statements. 

This study is a follow-up to a previous paper (pre-print available at: https://psyarxiv.com/zkjyr/) showing that children make inferences about unmentioned groups from generics when the mentioned and unmentioned groups belong to the same social dichotomy. 

## For lab members who are running the study on computers where the study has already been installed:

### For computers that have Visual Studio (VS) Code: 
1) Locate the folder titled `pidi3cat` on the lab computer. This is likely installed on the Desktop. 

2) Open the folder with VS Code. You can possibly do this by right clicking on the folder (there might be an option that says "Open with Code"). If that option is not available, open VS Code, click "File" (on the top left corner), and then click "Open Folder". Find the folder for your study and open it. 

3) Open up a terminal. You can do this by clicking "Terminal" and then "New Terminal" on the top menu, or by clicking `CTRL` + `SHIFT` + `` ` ``. 

3b) If the study has never been ran on this computer before, type `npm install` into the terminal. This might take a moment. (However, if the folder is already on the computer, this step has likely already happened). 

4) Type `npm start` into the terminal. This starts the game. This might take a moment. Wait for the terminal to tell you that the app has been "compiled successfully."

5) Open up an internet browser (Firefox or Chrome tend to work best), and type `localhost:4200` into the URL. 

### For computers that don't have VS Code installed:
The steps are quite similar as above. You'll be opening the terminal directly and entering a few extra commands. 

2) Get inside the folder containing the app. E.g., if the app is located on your desktop, type `cd Desktop/pidi3cat`

Follow steps 4 - 6 described above. 

### Updating the game before running it:
Sometimes you might need to pull changes from Github. You will generally only have to do this when explicitly instructed that changes have been made to the gamw. In order to do this, you will need to be connected to the internet. 

1) Locate the folder titled `pidi3cat` on the lab computer. This is likely installed on the Desktop. Open the folder using VS Code. You can possibly do this by right clicking on the folder (there might be an option that says "Open with Code"). If that option is not available, open VS Code, click "File" (on the top left corner), and then click "Open Folder". Find the `pidi3cat` folder.

2) Open up a terminal. You can do this by clicking "Terminal" and then "New Terminal" on the top menu, or by clicking `CTRL` + `SHIFT` + `` ` ``. 

3) Type `git pull` into the terminal and press "Enter". This ensures you have the latest version of the study you are running. Close VS code and follow the steps below to run the game. 
