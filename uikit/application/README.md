#UIkit for Applications
Use to creat DB applications

*This is extension of [UIKit](http://getuikit.com/) you can create nd support easly and quickly DB applications.*

## Installation
```html
<head>
    ...
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.0.0-beta1/jquery.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/uikit/2.25.0/css/uikit.min.css"/>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/uikit/2.25.0/js/uikit.min.js"></script>
    ...
</head>
<body>
    ...
    <script src="js/application.js"></script>
</body>
```

## Initializing of data
HTML pages are cached, so the data that must be filled to withdraw with ajax request.

### HTML
```html
<select data-get="filte.to.json"></select>
...
<input data-get="file.to.vlue">
...
<textarea data-get="file.to.value"></textarea>
```

### JSON
```javascript
{ 
    data : {   
        id : 2, 
        text:"The text goes here"
    }
}
```