# What is New?
1- Add select PHP Version ( from 7.1 to => 7.4)<br>
2- Now you can create Laravel project or just install php, apache and mysql<br>
3- CentOS Support
# deploy_laravel_automatic
Deploy LAMP Stack and Laravel project to empty server with one command

From this script you can deploy LAMP Stack and Laravel Project with apache configurations with only one command.<br>

All you will need will be:<br>
1- Download this sell script to your empty server.<br>
2- chmod 777 laravel_auto.sh <br>
3- ./laravel_auto.sh to run the script<br>
4- Choose PHP version you want to install.<br>
4- Choose to install Laravel Project or not ( as you prefer ) Enter project name you want to be created under /var/www/html/<br>

You will only need to insert Enter when PHP Package is needed to be installed then enter your preferred MYSQL password you will need.<br>

For now it's working with Ubuntu and CentOS. Will add MacOS to it and other OS releases.

Thanks.

# Todo
- add support to CentOS release 6 and 8.
- add support to MacOS.
- add Laravel version choices.
- add some Laravel packages to choose from ( auth , passport ).
- set MYSQL password as entry from user.
- add support to another databases ( postgres , mongodb ).
- add npm installation. 

