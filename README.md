# ocpddhc

a brand new github repository to store the new ocpddhc website code.

OCPDDHC means Organisation Civile pour la Paix et la Defence des Droits de l'Homme en Centrafrique, created in 2012
after the chaos the Central African Republic was plunged in. The purpose of this website is to contain all of the data
and information related to the activities of the association.

## Running the application after cloning the repository
The following steps to clone and run the application.
1- clone the repository in your server's public directory, which is mostly www
git clone https://github.com/ocpddhc/ocpddhc.git

2- some environment related files are not pushed on Github so, make sure you have them before trying to run the application. the file name are .env, .gitignore, and .gitattributes. You may want to generate a new larave application using the command: laravel new myapplication, then copy these files from the newly generated application.

3- generate the hash key required to run the application: cd ocpddhc, then php artisan key:generate

4- generate a new application and copy the storage folder with its subfolders from the new application to the one you are trying to run.

5- open your browser and run the application.



