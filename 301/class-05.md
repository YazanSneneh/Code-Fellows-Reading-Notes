# HEROKU

 * it allow me to deploy my application.

##### View logs and Deploy the app to heroku
    * **Create an app on Heroku**, which prepares Heroku to receive your source code.
        `heroku create`.
    * When app create, a git remote (called heroku) is also created and associated with local git repository.    `git push heroku main`.
    * The application is now deployed. Ensure that at least one instance of the app is running: `heroku ps:scale web=1`.
    *  visit the app at the URL generated by its app name. shortcut to open the website. `heroku open`.
    * View information about your running app using following command :
      `heroku logs --tail`.
 * Press Control+C to stop streaming the logs. 


#### Getting Started on Heroku with Node.js
 * Node.js is an open source, cross-platform runtime environment, that is used to create server-side and networking applications.
 * node.js allow me to write javaScript code out of the browser.
 * first we have to install it (we did).

##### create a server using node.
1. create a javascript file and give it whatever name.
2. write the logic inside of it.
3. include the http.
4. create request handler.
5. make it listen to port, let say 3000
6. in terminal : **node fileName.js**
7. now check on the browser : https://localhost:3000


 * heroku come in handy here to deploy it on the internet.
 * package.json file for that purpose. It will contain project related information, such as name, version, description, and so on.
