
 **PYTHON NAOQI INSTALLATION GUIDE FOR MAC**

1)  Even If you are installing Naoqi drivers for pepper install from [here](https://community.aldebaran.com/en/resources/software/language/en-gb/field_software_type/sdk/robot/nao-2). As the python SDK are same for both Nao and Pepper supporting methods for both.

2)  Add environment variables :
```
$ export PYTHONPATH=${PYTHONPATH}:/path/to/python-sdk
$ export DYLD_LIBRARY_PATH=${DYLD_LIBRARY_PATH}:/path/to/python-sdk
```

3)  Run the command on terminal from where you have the file "pynaoqi_install.sh" 
```
$ chmod u+x pynaoqi_install.sh
$ ./pynaoqi_install.sh
```

4)  Run the Python which was default for Mac : `/usr/bin/Python`

5) To make it use on every terminal, copy the commands on step-2 to in .bash_profile
   And then run the command `source ~/.bash_profile`

6) Happy Pepper coding. You are good to go.

