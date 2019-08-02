# Curl

### Examples

- Send data with POST request:
```
curl -X POST URL -F "key=value"
```

- Send data with GET request and save the output in a file:
```
curl -G URL -d "key1=value&key2=value" -o output.log
```

- Send a custom header to a URL:
```
curl -v --header "User-Agent: admin" -X GET URL
```

- Make curl readable:
```
curl URL | tidy
```