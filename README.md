Important Linux Commands
====
1 Install git gui
====
 	a) command to install the git gui ===>  sudo apt-get install git-gui 
	b) command to start the git gui ===> git gui citool
2 Mongodb server
====
	a) http://docs.mongodb.org/manual/tutorial/install-mongodb-on-ubuntu/
3 Install skype
====
	a) sudo dpkg --add-architecture i386
	b) sudo add-apt-repository "deb http://archive.canonical.com/ $(lsb_release -sc) partner"
	c) sudo apt-get update
	d) sudo apt-get install skype
4 Open ssl error
==== 
	a) sudo apt-get install libssl-dev
5 Install git 
====
	a) sudo apt-get install git 
	b) git config --global user.name "Name Surname"
	c) git config --global user.email nick@company.com
6 Putty install
====	
	a) http://www.linuxtechi.com/install-putty-in-ubuntu/
7 Beyond compare
==== 
	a) http://www.scootersoftware.com/bcompare-4.0.2.19186_i386.deb //Downloading start and install the software using ubuntu software center.
8 Rbenv install
=== 
	a) http://www.gotealeaf.com/blog/how-to-install-ruby-on-rails-development-environment-for-linux
9 Postgres install
==== 
	a) sudo apt-get install postgresql libpq-dev
10 Some necessary command which are helpful in future 
==== 
	a) sudo apt-get install git-core curl zlib1g-dev build-essential libssl-dev libreadline-dev libyaml-dev libsqlite3-dev sqlite3 libxml2-dev libxslt1-dev libcurl4-openssl-dev python-software-properties
11 Sublime text-2 install
==== 
	a) sudo add-apt-repository ppa:webupd8team/sublime-text-2
	b) sudo apt-get update
	c) sudo apt-get install sublime-text
12 Mysql install
==== 
	a) sudo apt-get install mysql-client libmysqlclient-dev
	b) sudo apt-get install mysql-server
13 Odesk
==== 
	a) https://www.odesk.com/downloads/linux/odeskteam_3.2.59_ubuntu_12.04_amd64.deb //double click and install.
14 Elance
==== 
	a) download elance tracker "https://www.elance.com/tracker/TrackerSetup.deb"
	b) download adobeairinstaller from "http://airdownload.adobe.com/air/lin/download/2.6/AdobeAIRInstaller.bin"
	c) After Adobe AIR is downloaded, press Ctrl+Alt+T to open terminal.
	d) In your terminal, browse to the directory where you downloaded "AdobeAIRInstaller.bin" file and run following command --
		i) chmod +x AdobeAIRInstaller.bin
		ii) sudo apt-get install libxt6:i386 libnspr4-0d:i386 libgtk2.0-0:i386 libstdc++6:i386 libnss3-1d:i386 lib32nss-mdns libxml2:i386 libxslt1.1:i386 libcanberra-gtk-module:i386 gtk2-engines-murrine:i386
		iii) sudo apt-get install libgnome-keyring0:i386
		iv) locate libgnome-keyring.so
		v) sudo ln -s /usr/lib/x86_64-linux-gnu/libgnome-keyring.so.0 /usr/lib/libgnome-keyring.so.0
		vi) sudo ln -s /usr/lib/x86_64-linux-gnu/libgnome-keyring.so.0.2.0 /usr/lib/libgnome-keyring.so.0.2.0
		vii) sudo ./AdobeAIRInstaller.bin
	after successfully installation of adobeairinstaller.
		e) Then, double click on elance tracker and install
		f) after installation, Install java
		==== 
			a) sudo apt-get install openjdk-6-jre-headless
		
			OR follow this link, 	
		"http://www.mittalpatel.co.in/install_elance_tracker_adobe_air_and_java_in_ubuntu"
15 Chrome installation
==== 
	a) sudo apt-get install libxss1 libappindicator1 libindicator7
	b) wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
	c) sudo dpkg -i google-chrome*.deb  
17 FileZilla installation
==== 
	a) sudo apt-get install filezilla
18 Unrar file
==== 
	a) sudo apt-get install unrar-free
