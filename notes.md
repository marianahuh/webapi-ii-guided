| NON REST           | REST                                                              |
| :----------------- | :---------------------------------------------------------------- |
| /listAllHubs       | GET /hubs                                                         |
| /createHub         | POST /hubs                                                        |
| /updateHub         | PUT /hubs                                                         |
| /listHubMessages   | GET /hubs/:id/messages                                            |
| /listPostComments  | GET /posts/:id/comments                                           |
| /countPostComments | GET /post/:id/comments with an extra property { comments, count } |

read data from client:

- body (req.body)
- url parameters (req.params)
- query string
-
