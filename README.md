## Changelogger 


I always dream in a way to mantain my changelog up to date. That's why I decide yo create this simple scripts.

This changelogger is useful without a Continnuous Integration tool as Jenkins. 

In my case I use Jenkins for deploy my application and create the artifactory. 

Every Artifcatory is packed with a CHANGELOG created after execute this command

    $ changelogger > CHANGELOG

With this simple script you should be able to track every event in your application, in my case a run the command into the develop's branch.


### Installation

I like to access to my scripts in every place. 

$ cp -R changelogger /usr/local/bin/changelogger

$ chmod a+x /usr/local/bin/changelogger


