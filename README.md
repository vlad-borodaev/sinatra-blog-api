```shell
# Install rbenv

# Integrate rbenv into shell
rbenv init

# Install Ruby in the project
rbenv install 3.1.4

# Use a specific Ruby version locally, it creates the .ruby-version file
rbenv local 3.1.4

# Generate Gemfile
bundle init

# Add dependencies
bundle add sinatra
bundle add puma
...

# To start a multi-threaded Rainbows server
rainbows -c rainbows.conf
```