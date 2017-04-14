Some of PHP and Magento cli tools

# PHP

## PHP Code Sniffer
curl -OL https://squizlabs.github.io/PHP_CodeSniffer/phpcs.phar

### Examples
- `php phpcs.phar -s --standard=Zend app/code/community`
- `php phpcs.phar -s --sniffs=Zend.NamingConventions.ValidVariableName --standard=Zend app/code/community`

## PHP Copy Paste detector
wget https://phar.phpunit.de/phpcpd.phar
chmod +x phpcpd.phar
### Example	
- `php phpcpd.phar app/code/`

## PHP Metrics
curl https://github.com/phpmetrics/PhpMetrics/releases/download/v2.1.0/phpmetrics.phar
chmod +x phpmetrics.phar
### Examples
- `php phpmetrics.phar --report-html=myreport.html /path/of/your/sources`

## PHP Mess Detector
wget -c http://static.phpmd.org/php/latest/phpmd.phar

## PHPLoc
wget https://phar.phpunit.de/phploc.phar
chmod +x phploc.phar

## Other tools
wget https://phar.phpunit.de/phploc.phar
chmod +x phploc.phar

# Magento Specific
## Magerun
wget https://files.magerun.net/n98-magerun.phar
chmod +x ./n98-magerun.phar
### Examples
- `php n98-magerun.phar sys:info`
- `php n98-magerun.phar config:get dev/css/merge_css_files`
- `php n98-magerun.phar dev:theme:info`
- `php n98-magerun.phar admin:user:create [username] [email] [password] John Smith Administrators`

## Magescan (cli)
Download latest from https://github.com/steverobbins/magescan/releases
