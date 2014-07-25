# Weekly Work Log

Too often, a week passes by and I reflact back on it wondering what I actually accomplished. This log is my attempt to document where my job takes me on a week-to-week basis.

## July 21, 2014
* Formulate strategy for migrations sites and apps off our current production VM to newer VMs; share with colleagues
* Begun work of migrating Wordpress databases to new production MySQL database server (once all MySQL and Postgresql Dbs are migrated, the old VM will be upgraded and repurposed as a second production VM for Wordpress hosting)
* Misc. website maintenance efforts for arts.wisc.edu and adminexcellence.wisc.edu
* Migrated hrdesign.wisc.edu to DoIT Web hosting platform and integrated Shibboleth for authentication and group management via DoIT's Manifest service
* Retrofit responsive design CSS into the diversity.wisc.edu redesign
* Wrangled a Bash script together to use iconv to batch convert some old content files to UTF-8
* Converted adminexecellence.wisc.edu to a set of static files and deployed a staging version to DoIT Web hosting

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
