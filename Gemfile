source :rubygems

gemspec
gem "rest-client", :git => "git://github.com/opscode/rest-client.git", :branch => 'ma/ipv6'

# If you want to load debugging tools into the bundle exec sandbox,
# # add these additional dependencies into Gemfile.local
eval(IO.read(__FILE__ + '.local'), binding) if File.exists?(__FILE__ + '.local')
