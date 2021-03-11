require_relative './config/environment'
require 'sinatra/activerecord/rake'

task :console do
  require 'irb'
  ARGV.clear
  IRB.start
end

# Try Out The Following:
# Check that the class exists:

# Artist
# => Artist (call 'Artist.connection' to establish a connection) 
# View the columns in its corresponding table in the database:

# Artist.column_names
# => ["id", "name", "genre", "age", "hometown"] 
# Instantiate a new Artist named Jon, set his age to 30, and save him to the database:

# a = Artist.new(name: 'Jon')
# => #<Artist id: nil, name: "Jon", genre: nil, age: nil, hometown: nil>

# a.age = 30
# => 30

# a.save