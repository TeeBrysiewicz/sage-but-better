#<project-name> WordPress

<description>

##Project Initialization
1. `git clone git@github.com:kohactive/sage-but-better.git`
2. Change the root and theme directory names to `<project-name>`
3. Find and replace <project-name> with the project name used in step 2
4. Add a <description> above
5. Add the Migrate DB Pro connection information below
6. Replace <jaws-db-url> in app.json if using heroku
7. Remove this section from this readme

##Environment Setup
1. Create local database: `wp_<project_name>`
2. "Save as" `.env.php.sample` to `.env.php`
3. Change variables to match your setup

##Installation
1. `git clone git@github.com:kohactive/<project-name>.git`
2. Navigate your browser to the local site: http://localhost/<project-name>
3. Follow the WordPress install instructions
4. Activate Migrate DB Pro(license key is in 1password)
5. Pull from staging(connection string below)
6. `cd /path/to/<project-name>`
7. If you don't have the Gulp cli installed: `sudo npm install gulp-cli -g`
8. `./install.sh`

##Development
`./development.sh`  
To watch for changes:  
`./watch.sh`

##Staging
[<project-name>.herokuapp.com](http://<project-name>.herokuapp.com)

##Database
[Migrate DB Pro](https://deliciousbrains.com/wp-migrate-db-pro/)
* set up local dev install to **pull** staging db
* **DO NOT PUSH TO STAGING. MAKE DB EDITS ON STAGING & PULL.**

Connection info:
```
<staging wp admin connection info>
```

##Base Theme
[Sage docs](https://github.com/roots/sage)
