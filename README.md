# JSCounterByClickEvent
JavaScript click event increase number or counter by clicking

```HTML
<div id="container">
</div>

<input type="button" value="Next" id="next" />
```

```JS
 // Counter by click event
 let counter = 0;

 let id = document.getElementById('container');
 let next = document.getElementById('next');
    
 next.addEventListener('click', function() {

   counter++;
   id.innerHTML = counter;
 
 }); 
 ```
