# loaderMest.js
### <p align="left"><img src="https://img.shields.io/github/license/mestoness/loadermest.js?style=for-the-badge"/> <img src="https://img.shields.io/npm/v/loadermest.js?style=for-the-badge"/>  <img src="https://img.shields.io/npm/dt/loadermest.js?style=for-the-badge"/> </p>
## Author 
Ahmet Baki Memiş
## Contact
<a href="mailto:resistmaze@gmail.com">Use this address to contact me</a>
## NPM

```

npm install loadermest.js

```

## CDN

```html
<script src="https://unpkg.com/loadermest.js/dist/js/loadermest.min.js"></script>
```
## Usage
#### Default Options
``` javascript
 status: null,
 spinnerColor: "black",
 spinnerBackground: "white",
 spinnerSize: "3px"
```
#### Adjust as you want

```javascript

  loaderMest({
	status:true,
	spinnerBackground:"#0a3d62",
	spinnerColor:"white",
        spinnerSize: "4px"
  });
```

#### Example
```html
<!DOCTYPE html>
<html>
<head>
<script src="https://unpkg.com/loadermest.js/dist/js/loadermest.min.js"></script>
</head>
<body>
<script>	
loaderMest({
	status:true,
	spinnerBackground:"#0a3d62",
	spinnerColor:"white",
	spinnerSize: "5px"

});
</script>
</body>
</html>
```
### Usage for version 1.0.16 and previous versions is as follows

```javascript
  loaderMest({
	status:"on",
	spinnerBackground:"#0a3d62",
	spinnerColor:"white",
        spinnerSize: "4px"
  });
```
