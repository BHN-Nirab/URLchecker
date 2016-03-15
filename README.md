
# URLchecker

URLchecker is a tool for verifying the functionality of URL filtering.  URLchecker sends http GET requests to a target list of websites and sees if the target webserver properly responds.  This can be useful for determing what sites URL web filtering is actually blocking for end users browsers.

# Usage

**-s** List of websites to test against.  Must be one URL per line.  
**-o** Output file in CSV format

# Dependencies
Requests Library [http://docs.python-requests.org/en/master/](http://docs.python-requests.org/en/master/)
```
pip install requests
```