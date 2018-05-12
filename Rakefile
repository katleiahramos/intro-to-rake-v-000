desc 'outputs hello to the terminal'
task :hello do
  puts "hello from Rake!"
end

names :db do
  desc 'migrate changes to your database'
  task :migrate => :environment do
    Student.create_table
  end
end
