
To Set Up in Cloud9, run:

# Run all development in Cloud9 so we all have the same Dev environment # Do NOT push into master. Submit pull request. # We're using ruby version 2.4.0 and rails 4.2.11.

gem install rails -v 4.2.11


# for cloning the git repo, use the https link

https://github.com/Omar-Chowdhury/Xplor-new


cd Xplor

bundle install

# to run server

rails s -p $PORT -b $IP
