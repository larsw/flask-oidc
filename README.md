# flask-oidc-ext

[OpenID Connect](https://openid.net/connect/) support for [Flask](http://flask.pocoo.org/).
[![image](https://img.shields.io/pypi/v/flask-oidc.svg?style=flat)](https://pypi.python.org/pypi/flask-oidc)
[![image](https://img.shields.io/pypi/dm/flask-oidc.svg?style=flat)](https://pypi.python.org/pypi/flask-oidc)
[![Documentation Status](https://readthedocs.org/projects/flask-oidc/badge/?version=latest)](http://flask-oidc.readthedocs.io/en/latest/?badge=latest)
[![image](https://img.shields.io/travis/puiterwijk/flask-oidc.svg?style=flat)](https://travis-ci.org/puiterwijk/flask-oidc)

This library should work with any standards compliant OpenID Connect provider.

It has been tested with:
  - [Google+ Login](https://developers.google.com/accounts/docs/OAuth2Login)
  - [Ipsilon](https://ipsilon-project.org/)

---
### Project status
This project is *actually* in active development.

---
### Extension list
  - Added extra header option to requests `OIDC_EXTRA_REQUEST_HEADERS`. This adds the ability to add a `Host: <issuer>` header in environments where the issuer is no the same DNS as where the request is sent to. E.g `localhost` vs `127.0.0.1`.
