require 'rake'

desc "Run specs"
task :default => :spec

require 'rubygems'
require 'spec'
require 'spec/rake/spectask'
 
desc "Run the specs"
Spec::Rake::SpecTask.new do |t|
  t.spec_opts = ['--options', "spec/spec.opts"]
  t.spec_files = FileList['spec/**/*_spec.rb']
end
