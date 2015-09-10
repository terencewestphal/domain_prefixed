# Domain Prefixed 6.x-1.0-dev
Domain Prefixed extension allows database table prefixing for use with subdomains. 

**Description**  
The lines of code are assambled from a suggestions in the [issue queue](https://www.drupal.org/node/1953292) of the [Domain Prefix](https://www.drupal.org/project/domain_prefix) module (no longer maintained). 


**Requirements**   
* [Drupal 6.x](https://www.drupal.org/project/drupal)
* [Domain Access 6.x-2.x](https://www.drupal.org/project/domain)

**How to use**  
There is no user interface. All modifications have to be done in code. Edit the domain_prefixed.module and change this line according to your needed table prefixes. 

```php  
// Define tables to (copy and) load dynamically, modify at your ease
$tables = array('block', 'block_custom', 'menu_links', 'cache_menu');
```
