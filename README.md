rfxDB
=====

![alt tag](http://dl.dropboxusercontent.com/u/4074962/mc2ads/resources/images/rfx-usecase.png)

NoSQL Database for Reactive Fast Data Processing

* Query data RQL (Reactive Query Language)
* Processing fast data as real-time view, there are 3 kind of data would be stored queried:
  + behavioral data (game, interests, touch, impressions, click, view,...)
  + context data (location, time, referrer, lead , session, ...)
  + entity data (user, games, revenue, marketing compaign, products, Buy in-app items, ...)
* Data pipeline processing for "fast data"
* Design for lightweight Lambda Architecture

Ideas and implemented at mc2ads Lab (http://www.mc2ads.com) 

Adopted (Actor+Lucene+Redis)
* https://github.com/maxpert/RedisDirectory
* https://github.com/timboudreau/acteur
