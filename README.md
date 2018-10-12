# elk-example-spring-boot
elk 
Heroku 
## 0-create compte [heroku](https://devcenter.heroku.com/)
## 1-install Heroku
to install [Heroku](https://devcenter.heroku.com/articles/getting-started-with-java#set-up/)


## 2-Once installed, you can use the heroku command from your command shell.
Log in using the email address and password you used when creating your Heroku account

```sh
$heroku login

```


Authenticating is required to allow both the heroku and git commands to operate.

## 3-Prepar the App to Deploy

```sh
$cd My-App

```
First, create an app on Heroku, which prepares Heroku to receive your source code:
```sh
$heroku create

```

When you create an app, a Git remote (named heroku) is also created and associated with your local Git repository.

By default, Heroku generates a random name for your app. You can pass a parameter to specify your own app name.

Now deploy your code:
```sh
$git push heroku master

```

The application is now deployed. Ensure that at least one instance of the app is running:

```sh
$heroku ps:scale web=1

```

 Now visit the app at the URL generated by its app name. As a handy shortcut, you can open the website like so:
```sh
$heroku open

```
you can see your logs by this commande 

```sh
$heroku logs --tail

```
## 4-connect your project to Github by clicking on Github in Deployment methode







