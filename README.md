# Catch of the Day

This is my first React project that I did as part of the [React For Beginners by Wes Bos](https://reactforbeginners.com).  The purpose of this project was to create an
online fish market where all the features were created using React components.

## Getting Started

## Software requirements

- React 15.0.0

- Firebase 2.3.1

- LocalStorage

```
Note:  Please see package.json for additional details regarding dependencies.
       Also, Firebase 2.3.1 only works with the Firebase legacy platform.
```

## Create Firebase Account

 ```
 https://firebase.google.com
 ```

## Create Firebase Project

1.  `Click to console` in the upper hand of the web page.

2.  Click `Create New Project`

3.  Set `Project name` to `catch of the day`

4.  Click `Create Project`

## Update the Firebase Project path to your project

1. Replace `YOUR-FIREBASE-PROJECT-URL` with the URL that appears in the
   `Database` section within the Firebase console.  Thus, you'll need to
   update the following files:

   ```
   /path/to/project/scripts/components/App.js
   /path/to/project/scripts/components/Inventory.js
   ```

## Starting the local server

```
$ gulp
```

Note:  This will allow you to make changes to the running application without
       having to restart the server.

## Configuring Authentication

- create a Github application and connect it with Firebase console

  - on Github.com, https://github.com/settings/developers

  - enter `Application name` as

    ```
    Catch of the Day
    ```

  - enter `Homepage URL` as

    ```
    http://localhost:3000
    ```

  - enter `Application description` as

    ```
    Catch of the Day
    ```

  - enter `Authorization callback URL` as

    ```
    https://auth.firebase.com/v2/catch-of-the-day-cwt/auth/github/callback
    ```

  - click `Register application`

  - on Firbase.com console, navigate to `Login & Auth`

  - click the `Github` tab

  - enter `GitHub Client ID` and `GitHub Client ID`

- create a Facebook application and connect it with Firebase console

- create a Twitter application and connect it with Firebase console

  - on Twitter.com, https://apps.twitter.com

  - click, `Create New App`

  - enter `Name` as

    ```
    Catch of the Day
    ```
  - enter `Description` as

    ```
    Catch of the Day
    ```

  - enter `Website` as

    ```
    http://localhost:3000
    ```

  - enter `Callback URL` as

    ```
    https://auth.firebase.com/v2/catch-of-the-day-cwt/auth/twitter/callback
    ```

  - accept the `Twitter Developer Agreement` by clicking checkbox

  - click `Create your Twitter application`

  - on Firbase.com console, navigate to `Login & Auth`

  - click the `Twitter` tab

  - click `Enable Twitter Authentication` checkbox

  - enter `Twitter API Key` and `Twitter API Secret`

## Production Deployment

  ```
  TBD
  ```

## Support

Bug reports and feature requests can be filed against this project here:

* [File Bug Reports and Features](https://github.com/conradwt/catch-of-the-day/issues)

## License

Catch of the Day is released under the [MIT license](https://mit-license.org).

## Copyright

copyright:: (c) Copyright 2016 Conrad Taylor. All Rights Reserved.
