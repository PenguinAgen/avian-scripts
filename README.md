# Avian Scripts
A collection of all scripts for Nuix created by Avian

## Worker Side Scripts (WWS's)
All worker side scripts are located in the directory 'wss'.
WWS'es are run during loading of a case, and this allows them to do things regular scripts cannot.

### Usage
There are several ways to use a WWS, (see [here](https://github.com/kalapakim/SmackDown2016/wiki/Worker-Side-Scripting) for more information), but for Avian scripts, there is an especially easy way.
First download the entire repository to it's own directory.
In the downloaded repository there is a file called `wss_caller.rb`.
In that file, set the `path` variable to the location of the downloaded repository.
When loading data, in the settings menu, there should be a tab called 'Worker Script' with a single huge text field.
Copy the contents of `wwsCaller.rb` into this field and edit the list of scripts to whichever scripts you like.
Now simply load the case as usual.

For details on a specific WSS please read the pertaining readme.

### Available scripts
* Email Address Fixer