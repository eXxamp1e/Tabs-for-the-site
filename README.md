# Tabs-for-the-site
Tab script on native javascript


This script is accompanied by a visual layout. To view the code itself, go to the js folder and open the script.js file.

Usage:
The only thing you will need to replace for the script to work correctly are the classes that we set for the variables. 
That is, in the lines we change the standard classes in the script to our own, where:

let tab = document.querySelectorAll('.info-header-tab'),
    info = document.querySelector('.info-header'),
    tabContent = document.querySelectorAll('.info-tabcontent');

'.info-header-tab' is the class of our links by which we will switch the slider,
'.info-header' - parent element of links,
'.info-tabcontent' is the content class that will be displayed on.
