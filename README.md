# check-all-settings
A workflow to check settings of config.

Default Enterprise Framwork template include InitAllSettings.xaml and Config.xlsx file.
InitAllSettings can import key and value from "Settings", "Constants" and "Assets" of sheet in config file, and all of them is kept in a Dictionary object.
In this project, add in config file a "Checkings" sheet that have three types of configurable check and return message column.
Develop a new process CheckAllSettings.xaml that can be used to check all of item in config valuable.
