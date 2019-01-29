# express-dynamic-views

## Code
```hbs
{{!-- views/gallery.hbs --}}
<h1>Gallery</h1>

<div class="gallery">

  {{#each pictures}}
    <img src="/images/{{this}}.jpg" alt="{{this}}">
  {{/each}}
</div>
```

## Result
![image](https://user-images.githubusercontent.com/5306791/51925150-bbb68380-23ee-11e9-9a55-f8093957189d.png)
