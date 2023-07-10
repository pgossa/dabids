# dabids
This project aim to create an application which permit searcher to store and share their data while being able to run analysis script on their data.

curl -X POST -d 'username=admin&password=password' http://localhost:8080/login
curl -g -X POST -H "Content-Type: application/json" -d '{"query": "query{hello}"}' localhost:8080/graphql

curl -X POST -H 'Content-type: application/json' -d '{"query": "query { user { id,firstname,lastname,roles{name} } }"}' http://localhost:8383/


[Title](https://www.howtographql.com/graphql-go/1-getting-started/)

```
query {
	links{
    title
    address,
    user{
      name
    }
  }
}
```
```
mutation {
  createLink(input: {title: "new link", address:"http://address.org"}){
    title,
    user{
      name
    }
    address
  }
}
```



