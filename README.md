```javascript
module.exports = function(input, callback) {
  try {
    var result = JSON.parse(input)
    callback(null, result) }
  catch (error) {
    callback(error) } }
```
