<h6 align="left">
    <img src="https://cdnquakingaspen.s3.eu-central-1.amazonaws.com/quaking+aspen+logo+teal+full-02.png"  />
</h6>

# http-status-code
[Introduction](#Introduction)\
[Getting Started](#Started)\
[Example](#Example)\
[Contributors](#Contributors)\
[License](#License)
<h2 id="Introduction">Introduction</h2>
This module contains a simple library with a single class to define HTTP status codes
 
<h2 id="Started">Getting Started</h2>
In order to install, open the command prompt and type ✌️:

```
pip install http_status_code
```

The following status codes are available in the standard module:
General:
- Successful request: 																200
- Bad request:																		400
- You are not authorized:	            				 							403
- The required resource is not found:												404
- Request arguments (query string or body) validation error: 	            		410

Authentication
- Invalid credentials:																430
- Your account is inactive:															431
- Missing token:																	432
- The token is invalid:																433
- The token is expired:																434
- Wrong token error (related to refresh and access tokens)                          435
- You have logged out invalid credentials. Please log in again:						436

Database
- This record already exists:														630
- This record is related to other records. Therefore, it cannot be deleted:			631
<h2 id="Example">Example</h2>
In order to use refer to the following [example](https://github.com/Quakingaspen-codehub/http_status_code/blob/master/Example.ipynb)

<h2 id="">Contributors</h2>

This project exists thanks to all the people who contribute. [[Contribute](CONTRIBUTING.md)].
<a href="https://github.com/Quakingaspen-codehub/http_status_code/graphs/contributors">
""
</a>

<h2 id="License">License</h2>

This library is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.
