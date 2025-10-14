# baffle
Ruby on Rails testbed

Follow install instructions for Ruby and Rails from here:
https://guides.rubyonrails.org/install_ruby_on_rails.html#install-ruby-on-ubuntu

- (build-essential, git, libssl-dev and zlib1g-dev already installed.  rustc, libyaml-dev and libgmp-dev to be installed)
- Install Mise version manager
- Install Ruby using Mise (mise use -g ruby@3)
- Install Rails (gem install rails)
- (updated gems using gem update --system 3.7.2)
- Created new Rails app (ruby new baffle)

- Add a database table (bin/rails generate model Product name::string)
