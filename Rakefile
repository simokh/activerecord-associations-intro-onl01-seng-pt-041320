require_relative 'config/environment.rb'
require "sinatra/activerecord/rake"

desc "starts console"
# task :console do
#   Pry.start
# end
task :console do
  ActiveRecord::Base.logger = Logger.new(STDOUT)
  Pry.start
end