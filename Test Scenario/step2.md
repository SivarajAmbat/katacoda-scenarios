In this step, you will create an initial workspace and a starter app, and run that app locally to verify your setup

## Tasks

1. Create a new folder for your project and navigate to this folder:

`mkdir projects && cd projects`{{execute}}

2. Create a new angular project using the following command: 

`ng new HelloWorldApp`{{execute}} 

3. Respond to the prompts with following options: 

> - ? Would you like to add Angular routing? (y/N) **N** 
> - ? Which stylesheet format would you like to use? **PRESS ENTER** (To select the default CSS option)

4. Navigate into the HelloWorldApp folder. 

`cd HelloWorldApp`{{execute}} 

5. Type `ls` to view the contents of the startup project created by Angular-CLI. 

`ls`{{execute}}

6. Execute the below command to build and run the Angular project. 

`ng serve --host 0.0.0.0 --disable-host-check`{{execute}}

> The ng serve command launches the server, watches your files, and rebuilds the app as you make changes to those files. In your local setup, you can just execute `ng serve` and view the output at http://localhost:4200/.

7. Click the + symbol next to the Terminal tab and choose "Select Port to View on Client" and enter 4200 as port number. You should be able to see the default Angular application in your browser.

