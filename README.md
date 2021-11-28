# Smart_Attendance_Tracker
This app takes online/offline attendance taking to another level with its smart face detection and attendance tracking mechanism.
## About The Project

We have developed an attendance recorder which records attendance of the students using our face recognition model which has an accuracy of about 97%. 

We have managed to give all possible statistical analysis and hassle free management of attendance of their students.

Detailed explanation of how to run the project is given below.



### Built With

* [NodeJS](https://nodejs.org/en/)
* [ExpressJS](https://expressjs.com/en/starter/generator.html)
* [Python](https://www.python.org/)
* [OpenCV](https://opencv.org/)

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

Update to the latest version of npm
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/ariba2806/Smart-Attendance-Tracker.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Install Python packages
   
   ```sh
   cd ./Py-Scrpits 
   pip install requirements.txt
   ```

### Running the project
1. Start the express server from the root directory
   ```sh
   npm start
   ```
2. Start the flask server
    ```sh
    cd ./Py-Scripts
      python app.py
   ```
3. Start the mongo server
    ```sh
    mongod --dbpath YOUR_PATH
   ```
4. If possible change the user and password in ```mail.js``` file to your mail username and password
5. Then open ```localhost:3000``` in your PC and here is your attendance tracker
    

