# MaX Development Server

**MaX Development Server** is a development server setup script for Ubuntu 14.04 (tested with [Digital Ocean VPS](https://www.digitalocean.com/?refcode=751743d45e36) and Vagrant). **MaX Development Server** provides you with an environment to host websites written with PHP, Ruby (not yet implemented), ASP.NET, and Java. It utilizes **bleeding-edge technologies** and uses nginx as a reverse-proxy, providing you with the benefits of **super-fast** static file serving and the optimizations that come along with the built in Google pagespeed module.

## Features
+ 1 line installation

## Instructions
1. Set up a CentOS VPS (this script was built and tested CentOS WordPress with a 2GB 64-bit CentOS 6.4 [Digital Ocean VPS](https://www.digitalocean.com/?refcode=751743d45e36)
2. Log into the VPS with PuTTY (or another SSH client)
3. Enter `bash <(curl -s https://raw.githubusercontent.com/TimeTravelersHackMe/Ubuntu-Development-Server-Setup/master/setup.sh)`
4. Follow the prompts and prosper

# Using NVM or RVM as a User Without Root Priveledges
NVM and RVM are stored in /usr/local/. NPM, Node, and Ruby are all installed and available for all users. However, if a user without root priveledges wants to use a different version of NPM, node, or Ruby then they will have to either obtain root priveledges so they can access /usr/local files or they can change their NVM/RVM locations so that they reside in a folder that they have priveledges to.

For NVM:

`export NVM_DIR="/usr/local/nvm"`

For RVM:

`export rvm_path="/usr/local/rvm"`

## Benchmarks
To come (after I include a benchmarking suite)

## Technology Used
Too much to list. Check out setup.sh.
