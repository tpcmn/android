Getting Started
---------------

To get started with PAC-man for armv6, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository using the PAC-man armv6 trees, use this command:

    repo init -u git://github.com/tpcmn/android.git -b cm-10.1-legacy

Then to sync up:

    repo sync
	

Building PAC-rom
----------------

Currently supported Devices: P500, Cooper, Gio

To build the rom rom for one of the above given devices, run in terminal:

	Building for P500
		
		. build-pac.sh p500
		
	Building for thunderc
	 
		./build-pac.sh thunderc
		
	Building for Cooper
	
		. build-pac.sh cooper
