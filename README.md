# 3rdWEBTECHMiniProjectSubmission
(CLICK ON README.md and READ THIS IN CODE MODE )
3rd Sem WebTechMiniProject Submission
How to Run Code ->

1)Create a folder , and within that folder make another folder called backend
2)Navigate to parent folder either using cmd or vscode , and run the code "npm create vite@latest"
3)It will ask you name the project folder , name it as frontend , and choose ->react and then ->Javascript 
  and then run the commands "cd frontend ,  npm install ,  npm run dev"
4)This will create a new folder in the parent folder along with the backend folder already present
6)Install these libraries in the frontend folder to install them run this following command
  npm install @xyflow/react lucide-react axios react-bootstrap bootstrap react-router-dom react-modal

7)Now Install Libraries in the backend folder run this command in the backend folder 
  npm install express mongoose cors multer dotenv bcrypt jsonwebtoken body-parser nodemon
  Note use "npm install --save-dev nodemon" to download the library locally in your folder

8)Now go to backend folder and run the command 
  npm init
9) this should give you either one or two .json files 
    out of these two files go to package.json , and change   
    "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  }

  to 

    "scripts": {
    "devStart": "nodemon server.js"
  }
  and simply paste the files in the backend folder of this repository to the backend folder in you system
  (## Download the zip file of this repository)
10)Delte everything from the src folder of the frontend folder , and create two folders in it , one component and the other FrontJigs , and simply post given in this repository to the src folder, component and FrontJigs folder 
11)To run the code , first navigate to the frontend folder , run the code "npm run dev" and then navigate to backend folder and the run the command "npm run devStart"



  
  
