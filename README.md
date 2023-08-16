## ERP-PROJECT (Project Management Tool)
This is a project management tool used to manage company projects, project participants, progress, and project evaluations. The tool is built using .NET and Angular. The ERP-PROJECT tool is regularly managed and updated by the staff team of NCC.

-----
# Screenshots
![client](https://github.com/Duc22599/Test-NCC-Nguyen-Anh-Duc/assets/111440755/bbc35249-8945-497a-9c4d-fb1b3d22e0c0)
![OutsourcingProject](https://github.com/Duc22599/Test-NCC-Nguyen-Anh-Duc/assets/111440755/f535bc3c-0861-4591-99bb-054aac3129da)
![ProductProject](https://github.com/Duc22599/Test-NCC-Nguyen-Anh-Duc/assets/111440755/5b1cd91f-a3bb-4ff2-ab76-422d0e37b755)
![TrainingProjects](https://github.com/Duc22599/Test-NCC-Nguyen-Anh-Duc/assets/111440755/9205109b-7253-4fdc-b5e4-a8fb90d75418)
![TrainingRequest](https://github.com/Duc22599/Test-NCC-Nguyen-Anh-Duc/assets/111440755/329d8e7b-0db1-4b50-a0f5-7f824b126111)
![WeeklyReport](https://github.com/Duc22599/Test-NCC-Nguyen-Anh-Duc/assets/111440755/73010a66-1d3c-4944-8ff0-583b055d5b5c)
![WeeklyReport1](https://github.com/Duc22599/Test-NCC-Nguyen-Anh-Duc/assets/111440755/42bc3fc9-a153-4843-a800-e226cc090a99)

# FE

# Prerequisites
 Install Node.js which includes Node Package Manager version 14.20  

# ProjectManagementTemplate
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.15

## Installation
1. Install the Angular CLI globally: 
 - npm install -g @angular/cli@9.1.15

2. Clone the repository:
 ```bash
   $ git clone https://github.com/ncc-erp/ncc-erp-project
   $ cd ncc-erp-project
```

3. Install dependencies:
 - npm install 
 - If you encounter an error while running npm install, you can use the command npm install --legacy-peer-deps as a replacement for npm install.    
 - The command npm install --legacy-peer-deps is used to address issues related to installing dependencies in a Node.js project when versions of the dependent packages are not compatible with each other. 
    
## Development server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive/pipe/service/class/module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

-----

# BE: 
### Installation
1. Install the project dependencies:
- [ASP.NET Core SDK](https://dotnet.microsoft.com/download) (version 3.1.426)
- [Node.js](https://nodejs.org/) (LTS version)
- [Angular CLI](https://cli.angular.io/) (global installation)

2. Environment Setup
**Clone the project from the repository:**
```bash
$ git clone https://github.com/ncc-erp/ncc-erp-project
$ cd ncc-erp-project
```

### Run Application (ASP.NET) 

1. **Open apsnet-core folder in Visual Studio :**
   - Open the solution file projectManagement.sln in the aspnet-core folder using Visual Studio. 

2. **Choose the run mode:**
   - Select the run mode (Debug or Release) and enviroment (IIS Express or specific server) as needed. Edit the listening port (if necessary).

3. **Edit the listening port (if necssary):**
   - Open `launchSettings.json` in the `ProjectManagement.Web.Host/Properties`.
   - Find the entry corresponding to the project (ví dụ: `ProjectManagement.Web.Host`).
   - Change the value of `applicationUrl` to specify the port that the backend will listen on.

4. **Press F5 (or select Debug > Start Debugging) to run the project.**

application will be compiled and run in the enviroment you've chosen. Information about the listening port will appear in the Output window in Visual Studio.




