namespace :greeting do
desc 'outputs hello to the terminal'
  task :hello do
    puts "hello from Rake!"
  end

  desc 'outputs hola to the terminal'
  task :hola do
    puts "hola de Rake!"
  end
end

namespace :db do
  desc 'migrate changes to your database'
<<<<<<< HEAD
  task :migrate => :environment do
    Student.create_table
  end
  task :seed do
    require_relative './db/seeds.rb'
  end
end

task :environment do
  require_relative './config/environment'
=======
  task :environment do
    require_relative './config/environment'
  end

  task :migrate => :environment do
    Student.create_table
  end
end

task :seed do
  require_relative './db/seeds.rb'
>>>>>>> fe6c73732f68797dd65beccf91d227941de74d60
end

desc 'drop into the Pry console'
task :console => :environment do
  Pry.start
end
