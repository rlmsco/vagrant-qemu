source "https://rubygems.org"

group :development do
  # We depend on Vagrant for development, but we don't add it as a
  # gem dependency because we expect to be installed within the
  # Vagrant environment itself using `vagrant plugin`.
  # Removed dependency on non-open source version of vagrant
  gem "vagrant", :git => "https://github.com/rlmsco/viagrunts.git"

  gem "rake"
  gem "rspec", "~> 3.4"
  gem "rspec-its"
end

group :plugins do
  gem "vagrant-qemu" , path: "."
end
