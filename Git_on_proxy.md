## Getting git to work on a proxy server: 

	git config --global http.proxy http://proxyuser:proxypwd@proxy.server.com:8080

* change proxyuser to your proxy user
* change proxypwd to your proxy password
* change proxy.server.com to the URL of your 		proxy server
* change 8080 to the proxy port configured on 		your proxy server

If you decide at any time to reset this proxy and work without proxy:

	 git config --global --unset http.proxy

Finally, to check the currently set proxy:

	git config --global --get http.proxy