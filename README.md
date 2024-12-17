# Frontend-tutorial-Workshop
For workshop web development

# pre installation ( for window only)
| program     | Description |
| ----------- | ----------- |
| nvm step 1        | **https://github.com/coreybutler/nvm-windows/releases** <img src="https://github.com/user-attachments/assets/5da97c81-13df-4abe-aed3-a3f09de12aad" alt="nvm" width="600"  />|
| nvm step 2  |  ``` nvm -v ``` for checking version of nvm|
| Node.js  |  ``` nvm install 22 ```|


# pre installation ( for mac only) 
https://www.freecodecamp.org/news/node-version-manager-nvm-install-guide/
| Program     | Description |
| ----------- | ----------- |
| nvm step 1  | ```curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh``` |
| nvm step 2  |  ``` nvm -v ``` for checking version of nvm|
| Node.js  |  ``` nvm install 22 ```|

# init project
| command     | Description |
| ----------- | ----------- |
|run command in terminal ```npm create vite@latest``` |open terminal in vs code and paste ```npm create vite@latest``` and hit enter <img width="657" alt="Screenshot 2567-12-16 at 22 26 15" src="https://github.com/user-attachments/assets/96d82629-0e67-43f4-aecd-0083234491b5" /> |
|hit enter|<img width="657" alt="image" src="https://github.com/user-attachments/assets/e66b795c-86f9-4fde-a53e-09f5d35506ac" />|
|type your project name example "frontend"| <img width="604" alt="image" src="https://github.com/user-attachments/assets/42a300c5-beba-4981-9d86-065cf3761f63" />|
|select framework ```React``` and ```Typescript```| hit down arrow and enter <img width="600" alt="image" src="https://github.com/user-attachments/assets/a1932308-b622-4e53-8217-1064e43acacb" />|
|if finish your terminal will show | <img width="259" alt="image" src="https://github.com/user-attachments/assets/39b0f38d-6cfc-4f09-bb6c-74627d3f4a55" />|
|open project root directory| run command ```cd frontend``` in your terminal  |
|install package | ```npm install```|
|Run project| ```npm run dev```|
|If run success your terminal will show following picture. Then hit command and click  http://localhost:5173/ from your terminal |<img width="300" alt="image" src="https://github.com/user-attachments/assets/d3a9c910-c3f4-4eb6-9005-ef07653c9216" /> |

# for mac only
- before commit anything into github you need to create file ```.gitIgnore``` in your project (frontend folder) for prevent commit file .Ds_store
- in  file ```.gitIgnore``` type .Ds_store
- then you can commit via github desktop or git commandline

# how to commit using git command line
|command|description|
|-------|------------|
|```git init```|cd to your directory folder then type this command to annouce you will using git in this folder|
|``` git clone``` link| clone your git project to your computer ex:``` git clone https://github.com/fxhPhxrxchxyx/Frontend-tutorial-Workshop.git``` |
|```cd ``` folder name| open the folder to add some file and commit to github. ex: ```cd frontend```|
|```git add .```| add all file that you are implement to the git|
|```git commit -m``` message| commit file with the description message ex: ```git commit -m add homepage```|
|```git push```| push file into the github you can see your file upload into your repository in the github.com|
|```git pull```| in case you are implemend code with other you need to pull the repro to get uptodate code|
