# Useful Gems

## Authentication

**authorization and ACL:**  
gem 'cancan'

**Authorization Gem for Ruby on Rails with administrative interface. Semantic, Flexible, Lightweight (Competitor to Can-Can):**  
gem 'the_role'

**full on authorisation:**  
gem 'devise'

**used for invitation based devise stuff, works with devise:**  
gem 'devise_invitable'

**Use alternative (and even your own!) encryptors with Devise.**  
gem 'devise-encryptable'

**general authentication:**  
gem 'authlogic'

**multiple authentication methods:**  
gem 'omniauth'  
gem 'omniauth-facebook'  
gem 'omniauth-twitter'  
gem 'omniauth-google'


**used for multi-tenancy application work, eg basecamp style, multi users one account.:**  
gem 'acts_as_tenant'

**easier oauth functionality:**  
gem 'open_auth2'

**A production ready Rails Engine that turns your app into an Oauth2 Provider:**  
gem 'opro'

**Very simple Roles library without any authorization enforcement supporting scope on resource object. This library was intended to be used with CanCan and devise but should be generic enough to be used by any other authentication/authorization solutions:**  
gem 'rolify'

**encryption:**  
gem 'bcrypt-ruby', :require => 'bcrypt'


## Javascript

**used for making searchable multiselect with tags and searching. Not a gem better for searching lots of records, it uses ajax calls find at [jquery-token](https://github.com/loopj/jquery-tokeninput). Put into vendor > assets > javascripts folder. Then load via asset pipline... see [Railscasts 258-token-fields-revised](http://railscasts.com/episodes/258-token-fields-revised) for example:**  
gem 'chosen-rails'

**add jquery autocomplete:**  
gem 'rails3-jquery-autocomplete'

**ajaxify stuff - also add [jquery-pjax](https://github.com/defunkt/jquery-pjax):**  
gem 'rack-pjax'

**adds your ruby variables in your JS:**  
gem 'gon'


## Image & File Manipulation

**used for imagemagick manipulations:**  
gem 'rmagick'

**A ruby ImageMagick library that doesn't suck.(it is rad):**  
gem 'image_sorcery'

**used for image uploads, eg avatars, etc - [a gentle introduction to carrierwave](http://www.engineyard.com/blog/2011/a-gentle-introduction-to-carrierwave/) :**  
gem 'carrierwave'

**used for image uploads:**  
gem 'paperclip'

**Automatic Retina Image Handling for Rails 3.1+:**  
gem 'clear_eyes'


## System

**Seedbank allows you to structure your Rails seed data instead of having it all dumped into one large file. I find my seed data tended to fall into two categories. 1. Stuff that the entire application requires. 2. Stuff to populate my development and staging environments.:**  
gem 'seedbank'

**Advanced seed data handling for Rails, combining the best practices of several methods together.:**  
gem 'seed-fu', '~> 2.1.0'

**A Ruby gem for communicating with the Twilio API and generating TwiML (SMS):**  
gem 'twilio-ruby'

**handles events, like calling external apis etc:**  
gem 'eventmachine'

**Doorkeeper is an OAuth 2 provider for Rails:**  
gem 'doorkeeper'

**used for interacting with the cloud:**  
gem 'fog'

**used for restful api creation:**  
gem 'grape'

**used for backup:**  
gem 'backup'

**render custom json templates:**  
gem 'jbuilder'

**The Exception Notifier plugin provides a mailer object and a default set of templates for sending email notifications when errors occur in a Rails application.:**  
gem 'exception_notification'

**background job creation:**  
gem 'resque'

**[delayed job](https://github.com/collectiveidea/delayed_job):**  
gem 'delayed_job_active_record'

**runs multiple tasks at once for convenience:**  
gem 'foreman'

**used for scheduling things to run, like cron:**  
gem 'whenever'

**Simple, efficient message processing for Ruby:**  
Sidekiq uses threads to handle many messages at the same time in the same process. It integrates tightly with Rails 3 to make background message processing dead simple.  
gem 'sidekiq'

**Chronic is a pure Ruby natural language date parser:**  
gem 'chronic'

**Date and time formatting for humans:**  
gem 'stamp'

**versioning:**  
gem 'paper_trail'

**used for maintenance mode of sites:**  
gem 'turnout'

**need to install redis on mac:**  
gem 'redis'

**used for pretty urls:**  
gem 'friendly_id'

**used for better design patterns see [Railscasts Draper](http://railscasts.com/episodes/286-draper) :**  
gem 'draper'

**used for making a wizard eg installer:**  
gem 'wicked'

**Simple Ruby wrapper for the GitHub v2 & v3 API:**  
gem 'octokit'

**Helps you find your routes on a long Journey on Rails. Visit http://localhost:3000/rails/routes:**  
gem 'sextant'

**The Active Record Reputation System helps you discover more about your application and make better decisions. The Reputation System gem makes it easy to integrate reputation systems into Rails applications, decouple the system from the main application and provide guidelines for good design of reputation systems:**  
gem 'activerecord-reputation-system', :require => 'reputation_system'

**Keep model fields commented in your rails apps:**  
gem 'annotator'

**New Relic RPM Agent:**  
gem 'newrelic_rpm'

**Search:**  
gem 'ransack'


## Feature

**roll out particular features:**  
gem 'rollout'

**degrade features if failing or something like that:**  
gem 'degrade'


## CMS

**mountable blog engine:**  
gem 'monologue'

**refinery cms:**  
gem 'refinerycms'


## Mail

**used for viewing emails instead of sending tests:**  
gem 'mail_view'

**Catches mail and serves it through a dream:**  
gem 'mailcatcher'  
Type **mailcatcher** to launch  
Go to [http://localhost:1080/](http://localhost:1080/)  
Send mail through **smtp://localhost:1025**

**auto inline styles for emails:**  
gem 'roadie'

**An incoming mail processing microframework in Ruby: **  
gem 'mailman'


## WYSIWYG

**asset pipeline based ckeditor:**  
gem 'ckeditor_rails', :require => 'ckeditor-rails'

**ckeditor:**  
gem 'ckeditor', '3.7.1'

**used for WYSIWYG editor:**  
gem 'tiny_mce'


## Visual

**admin interface:**  
gem 'activeadmin'

**admin interface:**  
gem 'rails_admin', :git => 'git://github.com/sferik/rails_admin.git'

**adds auto haml support:**  
gem 'haml-rails'

**adds better form stuff:**  
gem 'simple_form'

gem 'zurb-foundation', :group => :assets # great starter for layouts

gem 'ZURB-foundation', :group => :assets # great starter for layouts...SASS

gem 'twitter-bootstrap-rails', :git => 'http://github.com/seyhunak/twitter-bootstrap-rails.git'

**yet another sass based twitter bootstrap:**  
gem 'bootstrap-sass'

**[sass-twitter-bootstrap](https://github.com/jlong/sass-twitter-bootstrap):**  
gem 'sass-twitter-bootstrap'

**cool semantic forms:**  
gem 'formtastic'

**used for pdf generation:**  
gem 'prawn'

**used for pdf generation:**  
gem 'wicked_pdf'

**json printing which is very pretty:**  
gem 'awesome_print'

**A simple, pure Ruby implementation of JSON code coloring:**  
gem 'pizzazz'


## Pagination

**hardcore pagination:**  
gem 'kaminari'

**general pagination:**  
gem 'will_paginate'

**bootstrap general pagination:**  
gem 'bootstrap-will_paginate'


## eCommerce

**online store:**  
gem 'spree'

**If you get an “Unable to resolve dependencies” error while installing the Spree gem you can try installing just the spree_cmd gem instead (which has minimal dependencies.):**  
gem 'spree_cmd'

**used for billing etc:**  
gem 'activemerchant', :require => 'active_merchant'


## Servers
**super fast concurrent web server:**  
gem 'puma'

**A very fast & simple Ruby web server:**  
gem 'thin'


## Other that I have no place for yet

**XML, HTML PARSING ETC:**  
gem 'nokogiri'

**geo mapping [geokit-gem](https://github.com/imajes/geokit-gem), also use the plugin [geokit-rails](https://github.com/imajes/geokit-rails) for advanced functionality:**  
gem 'geokit'

**Squeel lets you write your ActiveRecord queries with fewer strings, and more Ruby, by making the ARel awesomeness that lies beneath ActiveRecord more accessible.:**  
gem 'squeel'


## Development

group :test do
	gem 'cucumber-rails'
	
	gem 'database_cleaner'
end

group :test, :development do
	gem 'launchy'
	
	gem 'nokogiri'

	**used for creating api docs from rspec:**  
	gem 'rspec_api_documentation'

	**Helpful rake tasks for Heroku:**  
	gem 'heroku_san'
	
	gem 'capistrano'
	
	gem 'rspec-rails'

	gem 'email_spec'
	
	gem 'capybara'
	
	gem 'guard-rspec'
	
	gem 'growl_notify'
	
	gem 'cucumber'
	
	gem 'brakeman'
	
	gem 'annotate'
	
	gem 'nifty-generators'
	
	gem 'factory_girl_rails'

	**used for checking your code:**  
	gem 'rails_best_practices'
end