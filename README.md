https://github.com/snowplow/snowplow/wiki/Setting-up-PostgreSQL#1.2
https://mherman.org/blog/2017/08/23/building-a-restful-api-with-koa-and-postgres/

https://blog.innermonkdesign.com/how-to-use-mysql-and-asyncawait-with-your-koa-node-js-application/
use a json file as imported db data
https://github.com/hemanth/koa-rest/blob/master/controllers/books.js

http://www.wclimb.site/2017/07/12/Node-Koa2-Mysql-%E6%90%AD%E5%BB%BA%E7%AE%80%E6%98%93%E5%8D%9A%E5%AE%A2/
https://github.com/wclimb/Koa2-blog


# PostgreSQL
# https://www.quora.com/How-can-I-install-PostgreSQL-on-AWS-EC2-and-how-can-I-access-that
# http://revenant.ca/www/postgis/workshop/measurement.html
# https://gist.github.com/sholloway/4526778

# The task

Create an http based REST API that allows to search in a collection of POIs.
POI ("point of interest") is a data item that has a geo location among its attributes.
It is part of the task to design the structure of this POI (you can use restaurants, sport clubs, bikes etc.)
   
More details:

- The search should at least support bounding box queries on the POIs location (aka give me all items within this viewport)
- The API returns response type application/json
- The API should be implemented using  of Koa 2.x
- Make use of ES7 features where possible
- The final code should run on Node.js version 8 or higher
- The POI data can be loaded from a database or file

The project should be runnable from command line using npm or yarn (make up your mind).
The code is to be submitted as a public github repository.
Document your decisions, questions, open issues.
Do not spend more than two to five hours on the task
Hand it in even if you don't think it is done but your time is up.


# Bonus

Take one or more if you like

- Make a suggestion for a design that deals with POIs of different type
- Provide some form of user interface to make use of the API