require 'rubygems'
require 'puppetlabs_spec_helper/rake_tasks'
require 'rspec-system/rake_task'

# Customize lint option
task :lint do
  PuppetLint.configuration.send("disable_80chars")
  PuppetLint.configuration.send("disable_class_parameter_defaults")
end
