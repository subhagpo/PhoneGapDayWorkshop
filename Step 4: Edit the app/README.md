#Edit the App 

- Add hockeyapp registration code, in [root]/www/js/app.js::line 24
	    
	    hockeyapp.start(function() {
	        console.log("success");
	    }, function (err) {
	        console.log("error:" + err);
	    }, "[HockeyAppID]", true);
	
- In [root]/www/js/controller.js::line 154, simulate a crash. We are "bad" developers :)

        hockeyapp.forceCrash();
	
- Update the version in config.xml to 0.0.2, for this *bad* update.