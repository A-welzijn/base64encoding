# A-Welzijn Base64 encoding

v1.0.4

### Hoe het te gebruiken

```javascript
"dependencies": {
	"awelzijn-base64-encoding": "latest"
 }
```
```javascript
var app = angular.module('yourApp', [
	'awelzijn.base64encoding'
]);
```

Deze service wordt gebruikt om tekst te encoden naar Base64.

Je injecteert de service in je controller
```javascript
var controller = function (base64) {...}
controller.$inject = ['aWelzijnBase64Encoding'];
```
Je gebruikt de volgende methode
```javascript
var encoded = base64.encode("whatever");
```