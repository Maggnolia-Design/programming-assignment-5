# Infographic

Inforgraphic Homework:
Due end of Sunday, Corrections Due end of Wednesday.

Your infographic must use the following:
- Some kind of loop or map to programmatically generate a graphic
- You must utilize a helper function that you make
- The bulk of the graphic should not be 1 off code
- Your infographic should look interesting but does not need to make sense

Bonus points:
- Your infographic answers a specific hypothesis eg. Does bacon ipsum use shorter words at the begginning?
- Your data is multi dimensional, eg distance & number of photos over time is 3 dimensions
- You created the data you're visualizing (finding a paragraph and figuring out the properties) 


Example of a helper function:
```javascript
// helper function that makes random number between two other numbers
var myRandom = function(min, max) {
  return min + (Math.floor(Math.random()) * (max - min))
}


var randomArray = function(length) {
  var  outputArray = []
  for (var i = 0; i < length; i++) {
    // Using the helpler function myRandom
    outputArray.push(myRandom(0, 100))
  }
  return outputArray 
}
```

Resources:
Your probably best off making your own data set to start but here's some stuff:
[list of open data sets](https://github.com/caesar0301/awesome-public-datasets)
[data.gov](https://www.data.gov/)
[City of Boston](https://data.cityofboston.gov/)
[city of somerville](https://data.somervillema.gov/)
[MBTA api](http://realtime.mbta.com/portal) you might need an api key or want to just copy/paste this out.
