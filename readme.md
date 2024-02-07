# Load Balancer

[Credits to Ahmet Alp Balkan](https://www.youtube.com/watch?v=QTBZxDgRZM0)

```bash
npx http-server -p 5001
npx http-server -p 5002
npx http-server -p 5003
```

run
```bash
go run .
```

make some request and see the logs x5
```bash
curl localhost:8080 
```

## TODO
We can further improve this draft project and make it HTTP Load Balancer

### Things to consider when writing Production Ready Load Balancer
1. Load Balancing Techniques
2. Throttling
3. Concurrency