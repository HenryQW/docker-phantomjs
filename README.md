# phantomjs

Receives POST request and returns page content.

### Example

```
docker run -d --name phantomjs -p [your-port]:8910 wangqiru/phantomjs

curl --data 'url=[url]' [server-address]:[your-port]
```
