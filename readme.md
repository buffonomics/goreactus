# GoReactus:
An Activity SPA built with Go (REST API backend) and React. Bundled with webpack.
Created by Iyobo Eki.

To reduce the number of moving-part dependencies, goreactus uses a mock DB model to store data in memory.
Beego is the framework used to create the backend API.


## How to run
Run the go server by running the script runserver.sh.
Then open reactclient/index.html

### Backend Server:
sh runserver.sh

If you want to explore the REST API then...
https://localhost:8080/v1/{resource} where resource is either of [ user || activity ]


### Frontend Server:
sh runclient.sh

then visit
localhost:8081

Login using any of the provided credentials in the Login page.

ALSO, try interacting with the Activity Graph using various users.
