require 'bundler'

Bundler::GemHelper.install_tasks

task :console do
  require 'irb'
  require 'irb/completion'
  require 'token_authenticate_me' # You know what to do.
  ARGV.clear
  IRB.start
end
