jsprojectstartup
================

jsprojectstartup consists of a group of shell scripts to quickly create and setup a node.js project.  

All of these scripts assume that you are using either debian or ubuntu. They have been most tested on debian, my distro of choice.

Scripts
-------

bootstrap.bsh - Installs pip and nodeenv to create a nodeenv environment with a verion of nodeenv you specify. Usage:
'./bootstrap.bsh <location of nodeenv environment> <node version>'

createjsproject.bsh - Uses bootstrap.bsh to create a nodeenv environment and project structure for your project.
'/.createjsproject.bsh <project name> <project location> <node version>'

