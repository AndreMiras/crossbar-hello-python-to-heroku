# Crossbar hello:python to Heroku
Deploys the AutobahnPython based example to Heroku


This demo application shows it's possible to run the Crossbar router through Heroku.
See http://crossbar.io/docs/Setup-on-Heroku/ for more details.
Be careful, Free apps can only be active up to 18 hours of a 24 hour period. Find out more:
https://devcenter.heroku.com/articles/dyno-sleeping
It's recommended to stop and verify in your dashboard if the worker is running if you don't want to get charged.

```
heroku ps
heroku ps:stop web.1
heroku logs --tail
```
