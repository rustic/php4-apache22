# php4-apache22
This runs an old version of PHP 4.4.9 for an old application.

### Description and Usage
This runs an old version of PHP 4.4.9 for an old application with Apache 2.2. Example usage:

```
docker run -d -p 8080:80 --name apache -v /root/apache/www:/var/www apache_image
```

