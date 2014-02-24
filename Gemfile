# File: Gemfile


# Sources to draw gems from
source "https://rubygems.org"
# source 'http://gems.rubyforge.org'
# source 'http://gemcutter.org'


# Depend on a certain ruby version
ruby '2.1.0'


# Default gems used during any phase
group :default do # {{{

  # Framework
  gem 'rails'

  # Database
  gem 'mysql2'

  gem "acts_as_archival"
  gem 'paranoia'
  gem "activerecord-mysql-adapter"
  gem 'delayed_job_active_record'

  # Authentication/Authorization
  gem 'devise'
  gem 'devise-encryptable'

  gem 'active_link_to'

  gem 'jquery-rails'
  gem "nested_form"
  gem "kaminari"

  gem "daemons"
  gem "pdfkit"

  gem "browser"
  gem "gon"
  gem "rest-client"

  # View templating
  gem "slim"

  gem "copyright-header"

  # Payment
  gem 'paypal-sdk-rest'
  gem 'activemerchant'

  gem 'paper_trail'

  # Thumbnails
  gem 'carrierwave'
  gem "rmagick"
  gem 'tinymce-rails'

end # of group :default }}}

# Gems only using during development phase
group :development do # {{{
  gem 'better_errors'
  gem "binding_of_caller", :platform => [ :ruby_19 ]
end # }}}

# Test gems used only during development and testing
group :test do # {{{
end # }}}

# Gems used only for assets and not required in production environments by default.
group :assets do # {{{
  gem 'twitter-bootstrap-rails'
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'escape_utils', '=0.3.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby
  gem 'uglifier'
  gem 'turbo-sprockets-rails3'
end # of group :assets }}}

# Documentation gems only used to generate documentations
group :docs do # {{{
end # }}}


# vim:ts=2:tw=100:wm=100
