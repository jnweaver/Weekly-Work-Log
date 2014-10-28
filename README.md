# Weekly Work Log

Too often, a week passes by and I reflact back on it wondering what I actually accomplished. This log is my attempt to document where my job takes me on a week-to-week basis.

## October 27, 2014

* Changed the news site so it uses clipsheet JSON API instead of database connections
* Completed migration of four more Wordpress sites to new VM and Composer-based framework
* Fixed a bug in the newsletters Wordpress site having to do with SSL negotiation

## October 20, 2014

* Fix Apache reverse proxy configuration issue with our Jenkins instance
* Add feature to print bids Rails app to allow arbitrary number of other attachments to a bid
* Final changes to print bids app before going live
* Troubleshot a lingering bug in the news Rails app related to invalid characters in params corrupting cache keys
* Worked with @VidalQuevedo on brainstoriming some stories and scenarios for revising the alerts admin app UI
* Analyzed our Mapbox data and MobileUW traffic to estimate cost increase we'll see with MobileUW 2.0 switching to Mapbox for its maps

## October 13, 2014

* Migrated eight Wordpress site to new VM and moved them into our Composer-based Wordpress framework
* SSL and Shibboleth configuation for the sites migrating VMs this week
* Trained a web designer on working with Less
* Documented migrating Wordpress sites to our new Composer-based framework, as well as SSL and Shibboleth configuration
* Closed a few issues/feature requests related to our Parent Program newsletter
* Patched servers against POODLE vulnerability
* Trained a new editor on using Google Analytics

## October 6, 2014

* Fixed our broek Jenkins CI build tests for alerts
* Fixed my longstanding certificate issues in OSX Keychain!
* Built a vagrant for our Rails Alerts publishing app
* Research sourcemapping with grunt-less-contrib and Chrome developer tools

## September 29, 2014
* Documented known risks related to new Alerts publishing app
* Briefed alerts publishing app users one final time before production launch
* Launched alerts.wisc.edu and migrated wisc.edu to new VMs with minimal rollout issues
* Began researching issues with the new campus Microsoft Off Web App and its poor HTML email parsing capabilities

## September 22, 2014
* Finalized new [vote.wisc.edu](http://vote.wisc.edu) site and launched
* Finalized new [uc.wisc.edu](http://uc.wisc.edu) site and launched
* Finalized new [umark.wisc.edu](http://umark.wisc.edu) site and launched
* Patched our development Ubuntu box against Shellshock
* Definied monitoring tasks required for new wisc.edu and alerts.wisc.edu environments
* Various refactoring of alerts app code and design, with supporting tests
* Final design and browser testing on how wisc.edu consumes alerts.wisc.edu messages

## September 15, 2014

* Consulted on ongoing load testing of wisc.edu and alerts.wisc.edu environments
* Design and build new voter information website and new University Communications website
* Assisted with outstanding tasks on new University Marketing website
* Configiured new VM to use Shibboleth for Wordpress auth and campus Manifest group management utility

## September 8, 2014

* Developed initial version of University Makreting website portfolio using [Magnfiic Popup](http://dimsemenov.com/plugins/magnific-popup/)
* Other miscellaneous Wordpress development for University Communications and University Makreting websites

## August 25, 2014
* Refactored our Vagrant chef provisioning. Authored two cookbooks: [umark_wordpress_cookbook](https://github.com/UWMadisonUcomm/umark_wordpress_cookbook) and [umark_lamp_cookbook](https://github.com/UWMadisonUcomm/umark_lamp_cookbook)
* Restructured [commencement](http://commencmeent.wisc.edu) for Winter 2014 and Spring 2015 announcements
* Finished and deployed [Vice Chancellor for Research and Graduate Education](http://research.wisc.edu). Site used our new Wordpress skeleton deploying through Jenkins to DoTI Web Hosting
* Added a related posts feature to the On Wisconsin webstie to accommodate story packages
* Completed a massive data and tiles update to [map.wisc.edu](http://map.wisc.edu), including many OSM updates

## August 18, 2014
* Upgraded Ubuntu on shared development database and Jenkins/CI server
* Continued work on Vagrant, provisioning with Chef and Berkshelf for managing cookbook dependencies
* Designed and wrote the theme for new Vice Chancellor for Research and Graduate Education site. (Also wrote a simple rss-reader plugin to wrap the return of Wordpress's fetch_feed function in a PHP data object for cleaner integration with Timber. Will spin this off as an officiak WP plugin soon.)

## August 11, 2014
* Continued work on the new Wordpress bootstrap project using Composer
* Theme and style update to accommodate blog comments on the chancellor's blog for the first time
* Deep dive into Vagrant, chef and Berkshelf for configuring virtual environments for our Wordpress development

## August 4, 2014
* Configured Shibboleth for sustainability website
* Reviewed applications for web director position
* Fixed several minor issues with the WID website
* Upgraded30 Wordpress instances to 3.9.2
* Created a new Wordpress bootstrap git skeleton that uses Composer for managing WP core files and plugins (learned a lote more about Composer in the process!)
* Set up the deploy targets for the new wisc.edu environments

## July 29, 2014
* Migrated 20 MySQL and 2 Postgresql databases to new database server
* Upgraded Wordpress Core and plugins on ~ 12 sites; added Hypercache to many of these
* Installed autmysqlbackup script to new MySQL server for nighlt data dumps
* Submitted [Pull Request to Wordpress Timber project](https://github.com/jarednova/timber/pull/309) to fix menu bug
* Sat in on a design review for the new adult lifelong learning gateway
* Attended the Campus Communicators Content Strategy sessions 
* Refine the responsive grid for the diversity.wisc.edu redesign
* Migrate sustanability website to staging server; eventually moved into production
* Put new [diversity.wisc.edu](http://diversity.wisc.edu) into production
* Completed migration of MySQL and PostgreSQL databases to new production database server
* Attended On Wisconsin magazine redesign kickoff with Pentagram

## July 21, 2014
* Formulate strategy for migrations sites and apps off our current production VM to newer VMs; share with colleagues
* Begun work of migrating Wordpress databases to new production MySQL database server (once all MySQL and Postgresql Dbs are migrated, the old VM will be upgraded and repurposed as a second production VM for Wordpress hosting)
* Misc. website maintenance efforts for arts.wisc.edu and adminexcellence.wisc.edu
* Migrated hrdesign.wisc.edu to DoIT Web hosting platform and integrated Shibboleth for authentication and group management via DoIT's Manifest service
* Retrofit responsive design CSS into the diversity.wisc.edu redesign
* Wrangled a Bash script together to use iconv to batch convert some old content files to UTF-8
* Converted adminexecellence.wisc.edu to a set of static files and deployed a staging version to DoIT Web hosting
* Reviewed applications for an open digital marketing position in another division on campus
* Migrated 4 more Wordpress Dbs to new Db server and added Hyper Cache to each site

## July 14, 2014
* Implemented numerous front-end and back-end changes to alerts admin Rails app in advance of campus emergency exercise on July 17, 2014
* Conducted user training with campus emergency exercise participants
* Briefed colleagues on high-level architecture of Alerts Admin Rails app and static site deploys to public-facing, high-availability, load-balanced VMs
* Participated in campus emergency exercise on July 17, 2014, observing users as they used the new alerts management site for the first time. Add various new UI-imporvement issues to project tasks based on user observations
* Troubleshooting Apache perfemance issues introduced into our test VM after RedHat patching applied by DoIT

## July 7, 2014
* Compiled Google Analytics data about use of Departmental Directory link on wisc.edu in prep for a meeting about the directory
* Researched NetScaler app delivery controller to better understand how it can be configured to handle caching of alerts.wisc.edu
* Went through the [Redis tutorial](http://try.redis.io/)
* Reviewed [Sidekiq documentation](https://github.com/mperham/sidekiq/wiki)
* Migrated the dev database for alerts to our new production Postgres server
* Configured SSL on the test alerts app
* Integrated Shibboleth/NetID for authentication on the alerts app
* Pitched in with some CSS fixes on the diversity Wordpress site
* Reviewed applications for a job search I'm assiting on for the Division of Continuing Studies

## June 30, 2014

* Added Postgres backup scripts to Postgres servers
* Learned more about Postgres administration
* Produced and distributed first monthly Media Mentions e-report
* Revised WiscMail links on wisc.edu, adding popover feature to explain the change
* Tested and reviewed alerts.wisc.edu code
* Extended feature on uwpd.wisc.edu Wordpress site that allows for the hiding of featured images on story posts
