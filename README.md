# Unicorn Watcher
===============

Scout plugin to monitor when a unicorn master goes down. Checks for the expected pid and process name which are specified in the configuration options for this plugin within Scout.


## Current Version
1.0.0

## Requirements

* [Scout](https://scoutapp.com/)
* A valid PID to check for your unicorn master. 

## Installation
Same as any other Scout plugin. You can install it from within Scout or by manually placing unicorn_watch.rb on your server in /home/USER_RUNNING_SCOUT/.scout/
Here are a few links with more details about creating and installing Scout plugins
* [Creating a plugin](https://scoutapp.com/info/creating_a_plugin)
* [Scout help](https://scoutapp.com/help)

## Usage Instructions

Install plugin. Be sure to configure it within the Scout GUI so that it checks for the correct PID and process name. Then customize alerts in Scout to your liking so you are notified when the unicorn master goes away. 

