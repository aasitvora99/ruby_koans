require 'rubygems'
require 'rake'
require 'rdoc/task'  # ✅ modern replacement

task :default => :walk_the_path

task :walk_the_path do
  cd 'koans'
  ruby 'path_to_enlightenment.rb'
end

RDoc::Task.new do |rd|  # ✅ updated class name
  rd.main = "README.rdoc"
  rd.rdoc_files.include("README.rdoc", "koans/*.rb")
end
