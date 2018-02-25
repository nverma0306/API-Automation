# Assignment
N26 API Automation
### Prerequisite

### Tools:
* Postman app-latest version
* Npm
* Newman
* Nodejs
* Git
* Best Buy API Playground

### Programming Langauge: 
Javascript is used. Also used the inbuilt snippets in postman

# Tests Suite-APIAutomation_N26
It has following submodules corresponding to each APIs
* Products-Automated 5 available methods
* Stores-Automated 5 available methods
* Services-Automated 5 available methods
* Categories-Automated 5 available methods
* Utilities-Automated 2 available methods

### Project Architecture
> *The project is created using postman tool, its inbuilt snippets, javascript coding language. The complete project is divided in 5 submodules. Each submodule has basic CRUD operations as was provided by Best Buy Playground APIs. 
For Products, Stores, Services, Categories, Utilities APIs, for each method, validations are applied for schema verification, response time verification, request status, header content availability, different parameters availability and validations on diff values. 
Validations are also applied for verifying that different product, store, service, category after deletion, cannot be deleted again and are treated as bad requests.*

### Project File Structure & description

1. **APIAutomation_N26.postman_collection.json** File
    API Automation code
2. **N26_API_Automation.postman_environment.json** File
    Environment variables
3. **N26_API_AutomationSuite.bat** File
    clicking on this file will start the execution of automation test suite
4. **ReadMe.md** file
	Documentation about the project.
5. **newman** folder
    This folder contains generated report.
6. **API Automation Test Cases.xlsx** folder
    This folder contains the list of automated testcases

### How to run : 
1. Download or copy both json file in one folder. Note the path to this folder.
2. Copy the bat file at any place you wish to. Open the bat file in edit mode. Inside the bat file change the path to the location of json files on your local computer(copied in point 1 above). Also, at the same path the test report after the execution will be saved.
2. Make sure the local computer has git, Nodejs, Newman, NPM installed
3. Open the git-bash and follow below mentioned:-
 a. navigate to path on your local where you wish to have the playground api.
 b. Then clone the repository by using command
    git clone https://github.com/bestbuy/api-playground/
 c. navigate to api-playground by typing
    cd api-playground
 d. start the npm by typing in command
    npm start
 e. Once npm is started, open in your browser the playground api by typing in
    http://localhost:3030
 f. Now, double click on bat file to start the execution of Automation Suite.
 g. Now, this will create a Newman folder at the location which you have specified inside the bat file. 
 h. Navigate to the location and open the reports and verify the summary of execution of automation suite.