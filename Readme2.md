To Run Code 
//Step 1:
git clone [repository url]

OR

Open Terminal 

//Step 2:
cd [local repository]

Or
cd [ to project Directory]


//Step 3:
//Check package.json file and ensure scripts are notated as below:

"scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "test": "react-scripts test",
    "eject": "react-scripts eject"
  },

  //Step 4: 
/* Delete the node_modules folder and any 'lock' files such as 
yarn.lock or package-lock.json if present.*/

//Step 5: 
npm install

//Step 6:
npm start

npm audit fix
npm audit 


GIT Notation 

A - Added (This is a new file that has been added to the repository)

M - Modified (An existing file has been changed)

D - Deleted (a file has been deleted)

U - Untracked (The file is new or has been changed but has not been added to the repository yet)

C - Conflict (There is a conflict in the file)

R - Renamed (The file has been renamed)

S - Submodule (In repository exists another subrepository)