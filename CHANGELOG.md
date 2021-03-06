Changes
=======

v3.0.31-rc (20.02.2017)
-------------------------
    - update directories
    - fixes for redirects

v3.0.3-rc (17.02.2017)
-------------------------
    - fixes for https stuff scan
    - cleared internal wordlists
    - increased coverage
    
v3.0.3-beta (13.02.2017)
-------------------------
    - detect SSL cert requires
    - added 7150 directories
    - fixes for https subdomians
    - more unit coverages
    
v3.0.2-beta (31.01.2017)
------------------------
    - relieved of unnecessary dependencies
    - fully optimized code inside
    - user-friendly interface
    - multiple reporters (std,txt,json,html)
    - added external wordlists support
    - added external proxylist support
    - added wordlist shuffling
    - wordlst's prefixes
    - added multithreading control
    - dynamic and smart requests (cookies + accept headers)
    - apache index of/ and files detection
    - apache index of/ and files detection


v2.7.96 Before redesign (05.01.2017)
------------------------------------

* *v1.0.0* - all the basic functionality is available
* *v1.0.1* - added debug level as param --debug
* *v1.2.1* - added filesystem logger (param --log)
* *v1.2.2* - added example of usage (param --examples)
* *v1.3.2* - added posibility to use random proxy from proxylist (param --proxy)
* *v1.3.3* - simplify dependency installation
* *v1.3.4* - added code quality watcher
* *v1.3.5* - added ReadTimeoutError ProxyError handlers
* *v1.3.51* - fixed code style, resolve file read errors
* *v1.3.52* - code docstyle added
* *v2.3.52* - subdomains scan available! (param --check subdomains). Added databases
* *v2.3.54* - disabled treads error. Refactored
* *v2.4.62* - change port is available now! (param --port 8080). Code style fixes
* *v2.5.62* - HTTPS support added
* *v2.6.62* - added 19000 Possible directories!
* *v2.7.62* - added redirect handler (Beta)
* *v2.7.72* - added 52 directories, small changes for UI
* *v2.7.82* - added 683 directories
* *v2.7.92* - exclusion list added Data/exclusions.dat
* *v2.7.95* - large files definitions , bad requests detection handler
* *v2.7.96* - optimize debug levels (0 - 1 - 2 param --debug) , optimize imports