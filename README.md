``` 
* Generated by
* 
*      _____ _          __  __      _     _
*     / ____| |        / _|/ _|    | |   | |
*    | (___ | | ____ _| |_| |_ ___ | | __| | ___ _ __
*     \___ \| |/ / _` |  _|  _/ _ \| |/ _` |/ _ \ '__|
*     ____) |   < (_| | | | || (_) | | (_| |  __/ |
*    |_____/|_|\_\__,_|_| |_| \___/|_|\__,_|\___|_|
*
* The code generator that works in many programming languages
*
*			https://www.skaffolder.com
*
*
* You can generate the code from the command-line
*       https://npmjs.com/package/skaffolder-cli
*
*       npm install -g skaffodler-cli
*
*   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *
*
* To remove this comment please upgrade your plan here: 
*      https://app.skaffolder.com/#!/upgrade
*
* Or get up to 70% discount sharing your unique link:
*       https://app.skaffolder.com/#!/register?friend=5c126fc2803b9c6fca3d3509
*
* You will get 10% discount for each one of your friends
* 
```


```
   _____ _          __  __      _     _           
  / ____| |        / _|/ _|    | |   | |          
 | (___ | | ____ _| |_| |_ ___ | | __| | ___ _ __ 
  \___ \| |/ / _` |  _|  _/ _ \| |/ _` |/ _ \ '__|
  ____) |   < (_| | | | || (_) | | (_| |  __/ |   
 |_____/|_|\_\__,_|_| |_| \___/|_|\__,_|\___|_| 
 
                             _                __         _______          __     
     /\                     | |              / /        |  __ \ \        / /\    
    /  \   _ __   __ _ _   _| | __ _ _ __   / /_        | |__) \ \  /\  / /  \   
   / /\ \ | '_ \ / _` | | | | |/ _` | '__| | '_ \       |  ___/ \ \/  \/ / /\ \  
  / ____ \| | | | (_| | |_| | | (_| | |    | (_) |      | |      \  /\  / ____ \ 
 /_/    \_\_| |_|\__, |\__,_|_|\__,_|_|     \___/       |_|       \/  \/_/    \_\
                  __/ |                                                          
                 |___/                                                           
           _ _   _           ______ _          _                    
          (_) | | |         |  ____(_)        | |                   
 __      ___| |_| |__       | |__   _ _ __ ___| |__   __ _ ___  ___ 
 \ \ /\ / / | __| '_ \      |  __| | | '__/ _ \ '_ \ / _` / __|/ _ \
  \ V  V /| | |_| | | |     | |    | | | |  __/ |_) | (_| \__ \  __/
   \_/\_/ |_|\__|_| |_|     |_|    |_|_|  \___|_.__/ \__,_|___/\___|
                                         
 
```
                                       

This project was generated by Skaffolder

For more documentation visit https://skaffolder.com/#/documentation

--------------
### CONFIGURE
--------------

1. Set your firebase properties in:
    * For local/dev environments `src/environments/environments.dev.ts`
    * for production environments `src/environments/environments.prod.ts`

To get your firebase properties go to https://console.firebase.google.com and create a new project

2. Enable login with Google

    - Go to your Firebase console https://console.firebase.google.com
    - Go to Authentication section
    - Click on "Set Access method" and enable "Google Login"

--------------
### START APPLICATION
--------------

* To start the application open a terminal in this folder and type:

``` bash
$ npm install
$ npm start
```

Go to http://localhost:4200


* To run the service worker build with:
``` bash
$ npm run start:prod
```
this command will disable the autorefresh.

--------------
### USING SKAFFOLDER-CLI
--------------

With Skaffolder-CLI you can easily manage your Skaffolder project from command line and customize your generator template from your IDE.

Install Skaffolder-CLI with
``` bash
$ npm install -g skaffolder-cli
```

Login running the command
``` bash
$ sk login
```

Generate your project with the command
``` bash
$ sk generate
```

You can customize your generator template working with files in .skaffolder folder in your project root.

Please refer to https://skaffolder.com/#/documentation/skaffolder-cli for more information.
