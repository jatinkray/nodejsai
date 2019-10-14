# Node JS Application Insights Sample App

https://docs.microsoft.com/en-us/azure/azure-monitor/app/nodejs#sdk

#Install the app insights module:
npm install applicationinsights --save

https://github.com/Microsoft/ApplicationInsights-node.js/#configuration

By default setAutoCollectConsole is configured to exclude calls to console.log (and other console methods). By default, only calls to supported third-party loggers (e.g. winston, bunyan) will be collected. You can change this behavior to include calls to console methods by using setAutoCollectConsole(true, true).

https://github.com/Microsoft/ApplicationInsights-node.js/#configuration
