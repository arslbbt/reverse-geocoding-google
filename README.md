## Installation

```bash
$ npm i reverse-geocoding-google
```

## Examples

Basic

```js
var geocoding = new require('reverse-geocoding-google');
var config = {
    'latitude': 40.00403611111111,
    'longitude': 116.48485555555555,
    'key': 'YOUR Google api key'
};
geocoding.location(config, function (err, data){
	if(err){
		console.log(err);
	}else{
		console.log(data);
	}
});
