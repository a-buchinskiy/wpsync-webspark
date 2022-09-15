== Installation ==
	1. Install plugin from archive wpsync-webspark.zip
	2. Activate plugin
	3. Enjoy

== Future ==
	add setting page with:
		see statistic of last sync(time, status(done/error), next scheduled time, etc.)
		ability change cron interval
		ability run sync manualy(add button and maybe using js/ajax)
		also maybe request X times when return with error, for example add: private variable in object and then like check "if( error && $k < 3 ){ $k++; run_agin; }" reset $k every new request