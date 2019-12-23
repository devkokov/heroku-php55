This is the PHP 5.5 package used in my custom buildpack at devkokov/heroku-buildpack-php55.

To make changes:

1. Extract tar into src `tar -zxvf php-55.tar.gz --directory ./src`
2. Make changes as necessary
3. Compress back to tar `tar -zcvf php-55.tar.gz -C src .`
4. Upload to https://burnthebook.s3.amazonaws.com/buildpacks/php-55.tar.gz