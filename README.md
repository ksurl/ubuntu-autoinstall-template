# Instructions

1. Replace network IP's, USERNAME, HOSTNAME, SSH_PUBLIC_KEY, and the salted PASSWORD as needed
2. Serve these files from a web server  
a. e.g. `python -m http.server` in working directory
3. Boot from Ubuntu iso and press escape to get boot menu
4. Press F6 for boot options
5. Append `autoinstall ds=nocloud-net;s=http://IP:PORT/` and press enter
6. Install should proceed automatically