# functiona pine
This is a little JSON searcher, and viewer results into a d3 tree.

```npm
npm i
npm start
```

The application will run in [http://localhost:9001](http://localhost:9001)
The input allows searching for a specific node by its value inside the json loaded.

For example in this portion of json:
```json
"id":"a",
    "buscar":{
      "result": "alto",
      "demo":[
        {"id":1}
      ]
```

You can search by entering a node number (1) or node name ('alto'), not Object names or Array positions.
Inside the input field, write your search term and, if your term matches any of the existing nodes, then the path inside the tree is highlighted.
