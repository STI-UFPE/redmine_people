redmine_people
==================

Plugin for managing Redmine people with flexible permissions, avatars and attachments

* Local avatars for users
* Global users list with flexible ACL
* Attachments for users
* Person VCF export
* Next birthdays list
* New people list

Installation notes

Unarchive plugin to the plugins/ folder
run bundle install with exclusion not used DBMS (ex. bundle install --without sqlite postgresql)
run bundle exec rake redmine:plugins NAME=redmine_people RAILS_ENV=production


Code from: http://www.redmine.org/plugins/people
