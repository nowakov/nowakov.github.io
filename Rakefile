task :build do
  sh 'rm -rf javascripts'
  sh 'rm -rf stylesheets'
  sh 'rm -rf images'
  sh 'middleman build --verbose'
  sh 'mv -v ./build/* ./'
end
