---
title: "Title"
author: "Author"
date: "DATE"
output: 
  html_document:
     css: font-awesome-4.4.0/css/font-awesome.css
     self_contained: no

---
<i class="fa fa-renren fa-5x"></i>

To preview the correctly rendered html file, click 
<a href="http://htmlpreview.github.io/?https://github.com/FlorianWanders/FAonGitHub/blob/master/MWE.html" title="preview on htmlpreview.github.io" target="_blank">here</a>. 


# LA~~M~~P stack shell script install (minus the "M")
*This script is intented for use with Ubuntu 16.04 LTS*

!Note: 
- If you're using __AWS RDS__ or a cloud provider with RDS(Relational Database Services) and it supports the DB needed by the APP, there is no need to install SQL DB (in our case __Maria DB__.
- The PHP version is depended on your APP needs.
### Apps and versions
1. Apache
2. ~~MariaDB~~
3. PHP

The first command is to updated the apt repository:

``sudo apt-get update ``
