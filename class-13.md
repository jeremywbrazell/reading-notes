# Local Storage
- native applications have the OS typically provide an abstraction layer for storing & retrieving app -specific data like preferences or runtime state.
    - said values are stored in the registry, INI files, XML files, or some other place according to platform convention

## HTML5 Storage
- way for web pages to store named key/value pairs locally, within the client web browser
    - this data remains after you navigate away from web site, close your browser tab, exit your browser
    - this data is never transmitted to the remote web server

### Checking for HTML5 Storage
```
function supports_html5_storage() {
  try {
    return 'localStorage' in window && window['localStorage'] !== null;
  } catch (e) {
    return false;
  }
}
```
- otherwise, you can use Mondernizr to detect support for HTML5 Storage