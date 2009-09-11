begin
  require "hanna/rdoctask"
rescue LoadError
  require "rake/rdoctask"
end

Rake::RDocTask.new do |rd|
  rd.main = "README"
  rd.title = "API Documentation for Testicles"
  rd.rdoc_files.include("README", "LICENSE", "lib/**/*.rb")
  rd.rdoc_dir = "doc"
end

begin
  require "mg"
  MG.new("testicles.gemspec")
rescue LoadError
end
