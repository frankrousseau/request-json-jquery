request-json-jquery
===================

Make ajax request JSON simple with JQuery by writing your request like you were
on your Node.js server.

    request.get 'posts/comments' (err, data) ->
        console.log data[0].content

