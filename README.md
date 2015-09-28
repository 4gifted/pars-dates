# pars-dates
dates parser plugin for pars.js(https://github.com/4gifted/pars)

# API Usage Guidelines
```javascript
  var langCode = 'zh-cn'; // Simplified Chinese
  var datesPlugin = require('pars-dates');
  var instance = new Pars({
    lang: langCode, 
    // plugins
    plugins: {
      // register plugin 'dates'
      dates: datesPlugin
    }
    // other options
  });
  
  // parse the text
  instance.dates('text');
```
