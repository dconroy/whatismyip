# whatismyip
Simple PHP Script to return your true external ip, even works around proxies. This site is currently live at <a href='http://whatsmyip.me'>WhatsMyIP.me


The way this script works  by analyzing the $_SERVER variable ( an array containing information such as headers, paths, and script locations created by the webserver) and returning the most reliable IP address possible. Please note, the only address you can really trust is REMOTE_ADDR, because it is the source IP of the TCP connection and cant be changed by spoofing/changing an http header. While it is technically possible to bidirectionally spoof IP addresses at the <a href="http://en.wikipedia.org/wiki/Border_Gateway_Protocol" title="Border Gateway">Border Gateway level</a>, but you would have to have control over an ISP to do so. 
