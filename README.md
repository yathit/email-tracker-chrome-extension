Email Tracker Chrome Extension
==============================


A simple chrome extension to track opening status of email send from Gmail. 

See [Yathit Email Tracker for Gmail](https://chrome.google.com/webstore/detail/yathit-email-tracker-for/ldikiokclnbceabnlbkabmcacpiednop)

## How it works

An tracking image, 1x1 transparent pixel image, is added to email content. Most web server log IP address of any request along with referere and user agent.

IP address can used to locate geo position precision to City level.

## Backend server

This extension require a backend server to track image access log. We are using Google appengine, which also provide IP look up.




