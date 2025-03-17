---
layout: posts
title:  "Building an API"
date:   2025-03-17 08:54:16 -0500
categories: memory lane
---
Knowing how to build an API is an essential skill. You can see the importance of API's in our previous article here. The first step in building an API is choosing a technology stack to use. For the purposes of this article, we will use Node.JS. You will also need to use Express to make this stack work with your API. 

First, install Node. Then create a directory for your project and initialize it. Install express. Create the API with an index.js file. This file will establish requirement needs to have and use express, establish your app and port, and start your app. You will then run the server.

![Create the API](https://daytiffany-fs.github.io/memory-lane/images/createAPI.png)

In order for the API to work, you will have to create make endpoints for your users to get the correct information. First create routes allowing users to get all info, get one piece of info, edit info, and remove info. Test the routes to make sure they work and pull the right information based on the endpoint used.

![Make the Routes](https://daytiffany-fs.github.io/memory-lane/images/routes1.png)

![Finish the Routes](https://daytiffany-fs.github.io/memory-lane/images/routes2.png)

For life beyond your own pc, you will want to connect this information to a database. Intall mongoose and require it with your app. You can then deploy your API to a free service like Heroku or Render. These are the very basics of building and running an API.