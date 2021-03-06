# Hello App Engine

This is a simple Google App Engine web application using Java 8.

To deploy this to a new Google Cloud project follow these steps:

- Create a brand new Google Cloud Project
- Launch the Google Cloud Shell
- Run the following commands
    - `gcloud app create`
    - `git clone https://github.com/3wks/hello-appengine.git`
    - `cd hello-appengine`
    - `mvn appengine:deploy`
- Once the deployment is complete you can confirm the application is running by navigating to `App Engine > Versions` in the Google Cloud Console. Click on the link under `Version` to open the application in your browser.
- Launch the Code Editor and make some changes to `src/main/java/hello/servlet/HelloServlet.java`.
- Redeploy the application by running
    - `mvn appengine:deploy`
- Confirm the new version is deployed from `App Engine > Versions` 


