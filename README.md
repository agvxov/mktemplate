# mktemplate
This script attempts to eliminate user overhead of frequently coping a file to varying locations.
Mktemplate internally attempts to read a variable called "${MKTEMPLATE_HOME}".
This variable shall hold the path to the folder where templates are stored.
"Templates" are just files located at ${MKTEMPLATEHOME}.
Text files are processed through m4.
