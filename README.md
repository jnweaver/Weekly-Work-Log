# Weekly Work Log

Too often, a week passes by and I reflact back on it wondering what I actually accomplished. This log is my attempt to document where my job takes me on a week-to-week basis.

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
