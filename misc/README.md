# misc installs

sudo apt-get update

sudo apt-get install xclip

# Copies the contents of the id_rsa.pub file to your clipboard
xclip -sel clip < <file-to-copy-content-from>

sudo apt-get install tree

sudo apt-get install curl

sudo apt-get install default-jre -y
java -version

sudo apt-get install default-jdk -y
javac -version
	
sudo apt-get install maven -y
mvn -v


#https://github.com/rbenv/ruby-build#readme
ruby-build --definitions
ruby-build 2.4.0 ~/local/ruby-2.4.0 

# add ruby,rake a.o. to PATH
export PATH=$PATH:~/local/ruby-2.4.0/bin
ruby -v


#https://github.com/rbenv/ruby-build/wiki#suggested-build-environment

gem install travis -v 1.8.8 --no-rdoc --no-ri

travis -v


travis login --pro 


travis encrypt "travis-repo:travis-token" --add notifications.slack -r accountName/repoName


