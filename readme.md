# Craft 3 CMS mixed with Foundation Magic

## Installation

#### Install Craft 3 with composer

    [Instructions Here](https://github.com/craftcms/docs/blob/v3/en/installation.md)

#### Download this Repo and add to your project

    Unfortunately you can't create a composer project in a non-empty directory,
    and you cant clone a repo into a non-empty directory, so it's the best we got.

#### Clean up the .gitignore to include craft bits

    Remove all of the lines after:
    >Initial Craft ignores, remove after adding this scaffolding

#### Install packages.

    npm install

#### Love Life.


## npm Commands

#### Run default watch task
    npm run start

#### Build out the project
    npm run build

#### Build for production
    npm run production

###### Note: all needed files are put in /web/assets/ by default.
###### You may need to change this in config.yml for production.
###### You may also want to edit the .gitignore file to match it to your project needs.
