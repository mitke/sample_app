# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require File.expand_path('../config/application', __FILE__)
include Rake::DSL if defined?(Rake::DSL)
#require 'rake/dsl_definition'
require 'rake'

SampleApp::Application.load_tasks

module ::YourApplicationName  
  class Application
    include Rake::DSL
  end
end

