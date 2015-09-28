#Project 1

###Overview
The purpose of Project 1 is to set up the GitHub repositories, Digital Ocean Droplet, and deploy a basic web page that will serve as a main page for the other projects in this course.

This proved to be a great refresher for HTML and CSS, as well as how to utilize Git as well as setup hostnames.
I did have some trouble getting my domain name to direct to the main page, as it would still display the default Ubuntu Configuration document when going to www.benorman.com.
The trouble turned out that Apache was not running on the Droplet, as a result in a type-o in the configuration file directing the subdomain names to the associated files.
I fixed the syntax error and now everything is working properly.

###Live URL
The live Project one can be found here: 
[Live Project 1](http://p1.benorman.com)

###Other Details
On this page, there is a dropdown element for each of the 3 projects that are not P1.
The 'Site' links in these dropdowns are currently empty,
but the Github links do link to the GitHub repositories that I have already created.

###Plugins and Libraries
The only outside libraries used for this page were the ones included in Bootstrap.
Rather than include the files in my repository I have the page just loading the files from the CDN that Bootstrap is hosted on.

I used some of the basic code templates for some page elements but heavily modified most of it.
