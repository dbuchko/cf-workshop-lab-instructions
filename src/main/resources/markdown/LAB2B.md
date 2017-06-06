#Pivotal CF Workshop - Lab Instructions

##Java Module 2B

###Goals
* Get information on deployed application
* Stop and start the deployed application

###Steps
1. Get information about the currently deployed application using CLI apps command

	```
  > cf apps
  ```

	Note the application name for next steps App Name: ______________

2. Get information about your application instances using CLI `app` command.  (Substitute app name recorded in step one.)

	```
  > cf app <<app_name>>
  ```

    Observe the state of your app, as well as the basic statistics about it (eg. CPU, memory, etc.).

3. Stop the deployed application using the CLI

	```
  > cf stop <<app_name>>
  ```

    Attempt to navigate to the application home page.

4. Start the deployed application using the CLI

	```
  > cf start <<app_name>>
  ```

	Verify the app is running again by navigating to the home page.

5. Perform the same steps from the PWS (Apps Manager) web interface.
