[Reference Article](https://developer.mozilla.org/en-US/docs/Learn/Forms/Sending_and_retrieving_form_data)

## Client/Server Architecture
- a client (usually web browser) sends a request to server (Apache, Nginx, IIS, Tomcat) using the HTTP protocol

## On Client Side - How to Send Data

**Action Attribute**

Absolute URL
```
<form action="https://example.com">
```

Relative URL
```
<form action="/somewhere_else">
```

With No Attribute
```
<form>
```
**Method Attribute**

**Get Method**

**Post Method**

**Viewing HTTP Requests**

1. Open the developer tools.
1. Select "Network"
1. Select "All"
1. Select "foo.com" in the "Name" tab
1. Select "Headers"
