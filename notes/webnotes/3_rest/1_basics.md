#### What is RESTful Routing ?
- REST is a mapping between HTTP routes and CRUD operations
- It stands for REpresentational State Transfer
- Fundamentally there are 7 RESTful routes

| Name | Path | HTTP Verb | Purpose |
| -----|------|-----------|---------|
|Index|/articles|GET|List all articles|
|New|/articles/new|GET|Show new article form|
|Create|/articles|POST|Create a new article then redirect somewhere|
|Show|/articles/:id|GET|Show one specific article|
|Edit|/articles/:id/edit|GET|Show edit form for one article|
|Update|/articles/:id|PUT|Update an article then redirect somewhere|
|Destroy|/articles/:id|DELETE|Deletes an article then redirect somewhere|
