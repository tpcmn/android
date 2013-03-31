Getting Started
---------------

To get started with PAC-man for armv6, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository using the PAC-man armv6 trees, use this command:

    repo init -u git://github.com/tpcmn/android.git -b cm-10.1-legacy
    
Then to sync up:

    repo sync

Manually pull these repos to be up to date:

    git pull https://github.com/PAC-man/android_frameworks_base.git
    git pull https://github.com/androidarmv6/android_frameworks_native.git
    git pull https://github.com/PAC-man/android_vendor_pac.git
    git pull https://github.com/PAC-man/android_packages_apps_Settings.git
    git pull https://github.com/PAC-man/android_vendor_cm.git
    git pull https://github.com/androidarmv6/android_system_netd.git
    git pull https://github.com/androidarmv6/android_build.git

Building PAC-rom
----------------

To build the rom rom for one of the above given devices, run in terminal:

	
	Building for thunderc
	 
		./build-pac.sh thunderc
		
