---
layout: post
title:  "Getting started"
date:   2015-11-28 14:37:44
categories: tutorial
---

Clone the repository

```
	git clone https://github.com/midasvo/ownwhois-rest-api.git
```


Enter the directory

```
	cd ownwhois-rest-api
```

Install node packages

```
	npm install
```

Run the API

```
	node server.js
```

Use the API by substituting domainname.tld with the domainname and tld you want to look up

```
	http://localhost:3000/whois/domainname.tld
```