# Build JVM Runtime [![Follow](https://img.shields.io/twitter/follow/MissingClara.svg)](http://twitter.com/intent/user?screen_name=MissingClara)
Builds the JVM Runtime library (rt.jar) from source

### How?
 - Unzip ```src.zip``` to ```build/src``` folder
 - Edit the source if needed
 - Run ant in the root folder
 
 - The compiled classes will be located on ```build/classes```
 - The compiled jar will be located on ```build/dist/rt_custom.jar```
 - This can be used to compile other sources
 
### Example
```git clone https://github.com/FFY00/Build-JVM-Runtime```
Paste the source in the ```src``` folder and edit
```ant```

#### File Structure
```
root
│   build.xml  
│
└───build
    |
    └───classes
    |   └───...
    |
    └───dist
    |   |   rt_custom.jar
    |
    └───src
        └───...
```

### Contributors
 - [**FFY00**](http://twitter.com/intent/user?screen_name=MissingClara) - Maintainer
