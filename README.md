# Angular-MultipleApps-in-single-application
## Add a new Project to Workspace
Now, to create a new app under the workspace, we need to use the ng generate application command The first app created is marked as the default app

run `ng new <folder name> --createApplication="false"`

example :`ng new angularMultiapp --createApplication="false"`

The above command creates folder with the name angularMultiapp  and configures the workspace. It does not create any apps.
`cd angularMultiapp`
# Add a new Project to Workspace
Now, to create a new app under the workspace, we need to use the ng generate application command The first app created is marked as the default app
syntax `ng generate application <application-name>`
example `ng generate application example-a`

# Run the App
There are three ways in which you can run the app.

1.One is to use the `ng serve <application-name>`

2.Use the --project flag `ng serve --project="example-a"`

3.Open the angular.json and locate the defaultProject and change the name of the project to your application name and run ng serve
# Add Another Project to the workspace
run `ng generate application example-b`
# Building the App for Production
run `ng build --prod --project="<application-name>"`
example : `ng build --prod --project="example-a"`
# dist folder
The dist folder now has a folder for each of the new app.
