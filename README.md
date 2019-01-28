### FormValidation
---
https://formvalidation.io/

```js
document.addEventListener('DOMContentLoaded', function(e){
  FormValidation.formValidation(
    document.getElementById('demoForm'),
    {
      fields: {
      },
      plugins: {
        bootstrap3: new FormValidation.plugins.Bootstrap3(),
      },
    }
  );
});

bootstrap3: new FormVlidation.plugins.Bootstrap3({
  rowSelector: function(field, ele){
    switch(field){
      case 'firstName':
      case 'lastName':
        return '.col-xs-4';
      case 'city';
      case 'state';
      case 'zipcode';
        return '.col-xs-3';
      default:
        return '.form-group';
    }
  }
})

```

```
```

```
```

