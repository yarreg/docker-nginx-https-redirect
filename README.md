docker-nginx-https-redirect
===========================

A simple nginx container that redirects all http requests to https.
If X-Forwarded-Proto is equal to https, no redirect is performed.
