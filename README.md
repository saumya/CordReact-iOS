Cordova iOS Platform Application
=============================
 - It uses the platform specific workflow to create the Cordova project.
 - Then uses a [build JS file created from a ReactJS][1] application.

### Running the applciation

 From inside the application forlder
```
./cordova/run ios
```


### Plugman to add plugins

 From `inside project` folder
```
plugman install --platform ios --project . --plugin cordova-plugin-device
```
 
 From `any where` in the system
```
plugman install --platform ios --project /path/to/cordova/project/folder --plugin cordova-plugin-device
```



[1]: https://github.com/saumya/CordReact-JS

