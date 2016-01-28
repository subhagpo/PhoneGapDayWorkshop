#Edit the App 

- Add hockeyapp registration code, in app.js::line 24
	    
	    hockeyapp.start(function() {
	        console.log("success");
	    }, function (err) {
	        console.log("error:" + err);
	    }, "[HockeyAppID]", true);
	
- In Controller.js::line 154, simulate a crash. We are "bad" developers :)

        hockeyapp.forceCrash();
	
- Update the version in config.xml, for this *bad* update.