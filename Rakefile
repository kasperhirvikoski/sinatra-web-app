require 'rake/packagetask'

Rake::PackageTask.new('sinatra-web-app', '1.0.4-SNAPSHOT') do |task|

  task.need_tar_gz = true
  task.package_files = FileList['.ruby-gemset', '.ruby-version', 'Gemfile', 'app/*/*', 'config.ru']

end
