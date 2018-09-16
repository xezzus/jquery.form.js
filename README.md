# Install

```cmd
bower install getform
```

# Example

```html
<div id="form">
  <div><input type="text" name="name"></div>
  <div><input type="text" name="email"></div>
  <div><input type="text" name="phone"></div>
  <div><button name="registration" type="button">Registration</button></div>
</div>
```

```javascript
$(function(){
  $('#form').getform(function(e){
    console.log(e);
  });
});
```

```json
{
 "element":[Object],
 "form":{
  "name":"",
  "email":"",
  "phone":""
 },
 "name":"email",
 "type":"input",
 "value":""
}
```
