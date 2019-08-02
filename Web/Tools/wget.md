# wget

- Send data with POST request:
```
wget --post-data "key1=value&key2=value" URL -O output.log
```

- Send a custom user-agent to a URL:
```
wget -U 'admin' -O - URL 2>/dev/null
```
###### -O - is used to print the result in the standard output
###### 2>/dev/null skip all the standard errors

- Look for files/directories available on an URL:
```
wget --spider -r --no-parent URL
```

- Send a custom header to a URL
```
wget -d --header="Header: true" URL
```