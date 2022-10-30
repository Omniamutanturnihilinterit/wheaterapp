# OmniaMutantur-WeatherNavigation App
A weather application using OpenWeatherMap API and GeoDB API with places autocomplete, with React skills. <br/>

## WeatherNavigator App Overview:<br/>
![Screenshot](https://github.com/KrystalZhang612/WeatherNavigation-App/blob/newbranch/nyc%20weather%20overview1.png)<br/> 
![Screenshot](https://github.com/KrystalZhang612/WeatherNavigation-App/blob/newbranch/san%20jose%20weather%20overview2.png)<br/> 
![Screenshot](https://github.com/KrystalZhang612/WeatherNavigator-App/blob/newbranch/weather%20navigation%20app%20overview.png)<br/>
![Screenshot](https://github.com/KrystalZhang612/WeatherNavigation-App/blob/newbranch/berlin%20weather%20overview4.png)<br/>
![Screenshot](https://github.com/KrystalZhang612/WeatherNavigation-App/blob/newbranch/paris%20weather%20overview5.png)<br/>
![Screenshot](https://github.com/KrystalZhang612/KrystalZhang-WeatherNavigation-App/blob/newbranch/los%20angeles%20weather%20overview3.png)



# :hammer_and_wrench: Developing Languages, Tools, and Techniques Needed
[Visual Studio Code IDE 2022](https://code.visualstudio.com)<br/>
[NodeJS(node-v16.17.1-x64)](https://nodejs.org/ca/blog/release/v16.17.1/)<br/>
[JavaScript](https://www.javascript.com)<br/>
[React JS App](https://reactjs.org/docs/create-a-new-react-app.html)<br/>
[CSS3](https://en.wikipedia.org/wiki/CSS)<br/>
[HTML5](https://en.wikipedia.org/wiki/HTML5)<br/> 





<div>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" title = "Windows" alt = "Windows" width= "60" height = "60"/>&nbsp;
  <img src = "https://github.com/devicons/devicon/blob/master/icons/visualstudio/visualstudio-plain.svg" title = "Visual Studio Code" alt = "Visual Studio Code" width= "60" height = "60"/>&nbsp; 
  <img src = "https://github.com/devicons/devicon/blob/master/icons/nodejs/nodejs-original.svg" title = "Node.JS" alt = "Node.JS" width= "60" height = "60"/>&nbsp; 
  <img src = "https://github.com/devicons/devicon/blob/master/icons/react/react-original.svg" title = "React JS App" alt = "React JS App" width= "60" height = "60"/>&nbsp; 
  <img src = "https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title = "JavaScript" alt = "JavaScript" width= "60" height = "60"/>&nbsp; 
  <img src = "https://github.com/devicons/devicon/blob/master/icons/css3/css3-original.svg"  title = "CSS3" alt = "CSS3" width= "60" height = "60"/>&nbsp; 
  <img src ="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg"  title = "HTML5" alt = "HTML5" width= "60" height = "60"/>&nbsp;
  
  
</div>

- [Method pushing Vscode from Windows system to Github branch](https://stackoverflow.com/questions/45891052/vs-code-how-to-use-github-with-existing-local-project):<br/>
In Vscode Terminal: <br/>
`git init .`<br/> 
`git config --global user.name <yourGitHubAccount>`<br/> 
`git config --global user.email <yourGitHubEmailAccount>`<br/> 
`git add .`<br/>
`git status`<br/> 
`git commit -m "COMMIT MESSAGE"`<br/> 
`git remote add origin https://github.com/<yourGitHubAccount>`<br/>
`git push -u origin master`<br/>
- Method replacing main branch with the new branch in Pull request:<br/>
Change New Branch in Github account `branches` section into Default Branch. <br/>

# Build 
[Method to Run & Test the Project Locally](https://github.com/KrystalZhang612/KrystalZhang-WeatherNavigation-App#method-to-run--test-the-project-locally)<br/>
[Prerequisites & Setups](https://github.com/KrystalZhang612/KrystalZhang-WeatherNavigation-App#prerequisites--setups)<br/>
[Debugging&Troubleshooting](https://github.com/KrystalZhang612/KrystalZhang-WeatherNavigation-App#debuggingtroubleshooting)<br/> 
[Synchronous Developing Notes](https://github.com/KrystalZhang612/KrystalZhang-WeatherNavigation-App#synchronous-developing-notes)<br/>
[Testing Results](https://github.com/KrystalZhang612/KrystalZhang-WeatherNavigation-App#testing-results)<br/>

# Contribution
[Author](https://github.com/KrystalZhang612/KrystalZhang-WeatherNavigation-App#author)

# Compatibility
|   OS             | Supported          |
| -------          | ------------------ |
| Windows 10       | :white_check_mark: |

# Method to Run & Test the Project Locally

### Download the project to local directory. 
### In local console, locate to the project direcctory.
### Run `npm install`
### Run `npm i react-select`
### Run `npm run start`
### Then test the App at http://localhost:3000/
### `C+CONTROL` to exit from the App. 

# Prerequisites & Setups
## ***Getting API Keys:***
To find open APIs, go to [GeoDB Cities](https://rapidapi.com/wirefreethought/api/geodb-cities/)<br/>
Sign up, and subscribe to the `GeoDB Cities API Test` -> `Endpoints` -> `Cities`<br/>
Then we have all code snippets and optional parameters to choose. <br/>
Go to [OpenWeather](https://openweathermap.org/): <br/>
Sign up. In My Account generated my unique API keys and services. <br/>
In `Windows Terminal`:<br/>
`npx create-react-app react-weather-app`<br/>
This will take a few minutes to install the React App packages, it is ready once terminal says:<br/>
`we suggest that you begin by typing:`<br/>
`cd react-weather-app`<br/>
`npm start`<br/>
`Happy hacking!`<br/>
Open the created folder in the local address with Vscode IDE.<br/>
## ***Setups: Creating the application and installing packages:***
In Vscode Terminal, install two essential prerequisite packages before starting:<br/>
`Npm i react-accessible-accordion`<br/>
## ***Activate React app:***
`Npm run start`<br/>
React app setups and activation work if we are redirected automatically by Node.JS to `localhost:3000` and message in Powershell terminal returns:<br/>
`Compiled successfully!`<br/>
`...`<br/>
