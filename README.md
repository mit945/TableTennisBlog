# TableTennisBlog

 A platform for table tennis players to communicate idea via comments and upvotes.

## Link :

 Aws EC2 Link: ec2-52-43-246-104.us-west-2.compute.amazonaws.com

## Application Feature

   - Other article links suggested within an article 
   - Allow user to upvote an article 
   - Allow user to comment 

## Tasks

  - [x] `Create-react-app` for froent-end
  - [x] Import React Router to set up resources for backend uses 
  - [x] Create 404 Page 
  - [x] Set up Express server on set up get/post routes  
  - [x] Import data in JSON and check status through Postman
  - [x] Create Upvote functions
  - [x] Commenting functionality
  - [x] Edit About page and Home page with CSS
  - [x] Deploy via EC2 instance

## Article structure in MongoDB 

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