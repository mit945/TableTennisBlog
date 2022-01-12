# TableTennisBlog

A platform for table tennis players to communicate idea via comments and upvotes.

## Application Feature

- Other article links suggested under each article page
- Allow user to upvote an article
- Allow user to comment

## Usage

1. Clone the app

```
git clone https://github.com/mit945/TableTennisBlog.git
```

2. Install Express

```
cd TableTennisBlog
npm i express
```

3. Run the app

```
npm start
```

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
