# winston-cloudwatch

An [Amazon CloudWatch](http://aws.amazon.com/cloudwatch) transport for [winston](https://github.com/flatiron/winston).

## Usage
``` js
  var winston = require('winston');
  
  //
  // Requiring `winston-cloudwatch` will expose 
  // `winston.transports.CloudWatch`
  //
  require('winston-cloudwatch');
  
  winston.add(winston.transports.CloudWatch, options);
```
