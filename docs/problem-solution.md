# 常见问题以及解决方法

> Unable to load PlatformApi from platform. Error: Cannot find module 'properties-parser'
  Unhandled error. ('The platform "android" does not appear to be a valid cordova platform. It is missing API.js. android not supported.')
  
原因是因为我只在根目录执行了npm install 没有在./cordova/ 目录执行
