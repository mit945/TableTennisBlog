#TableTennisBlog

 A platform for table tennis players to communicate idea via comments and upvotes.

## Link :

 Aws EC2 Link: [ec2-52-43-246-104.us-west-2.compute.amazonaws.com](http://ec2-52-43-246-104.us-west-2.compute.amazonaws.com)

## Application Feature

   - Other article links suggested under each article page
   - Allow user to upvote an article 
   - Allow user to comment 

## Tasks

  - [x] `Create-react-app` for froent-end
  - [x] Import React Router to set up routes for forntend
  - [x] Create 404 Page 
  - [x] Set up Express server on set up get/post routes  
  - [x] Import data in JSON format and check request logs  through Postman
  - [x] Create upvotes functions
  - [x] Create comment functions
  - [x] Edit About page and Home page with CSS
  - [x] Deploy via EC2 instance

## Data structure 

```javascript 

ArticleList = [
  {
	name: "my-article",
	upvotes: 0,
	comments: [],
  },
  {...},
  {...},
]

```  
## License
  
Copyright (c) 2019 I-han Chang
