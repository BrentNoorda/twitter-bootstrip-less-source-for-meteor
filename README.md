twitter-bootstrip-less-source-for-meteor
========================================

Twitter bootstrap less and javascript source, modified ever-so-slightly to drop in a Meteor project with their less package. For Bootstrap version 2.3.2

### why not use Meteor's bootstrap package?

Meteor already has a bootstrap package, but that is for the pre-complied download version which has all hardcoded values. This version is the raw .less files so you can change some parameters.

### prerequisites

Must have Meteor's less package installed

### how to use

Copy all of these files into your Meteor project folder. Then twitter is up and running. Parameters can be edited in the file `client/twitter_bootstrap/less/variables.lessimport`

### how this was made

Downloaded the twitter bootstrap files, renamed a lot of the "*.less" files to "*.lessimport", moved the two .png file and changed the paths to them, and finally renamed "bootstrap-popover.js" to "z000_loadlate_bootstrap-popover.js" so that it is loaded after the other js files.