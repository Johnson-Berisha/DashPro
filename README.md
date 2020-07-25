# DashPro
Welcome, Welcome
Need a free dashboard you're bloody lucky
```html
<h1>true</h1>
```

Today i will tell you how to get it an how i created it.
Let's start
<br>
<br>
<br>
First we start using the link tag
```html
<link rel="stylesheet" href="http://dashpro.netlify.app/dashpro.css">
```
Now were finished with that let's create the dashboard
Let's start, first we use the class name project
```html
<div class="project">
  
</div>  
```
Then we make another div called project__card
```html
<div class="project">
  <div class="project__card">
    
  </div> 
</div>  
```
Then we add the image make sure it's inside a link tag and the height of it is 400 and the width is 600 and the link tag should have the class name project__image
```html
<div class="project">
  <div class="project__card">
    <a href="" class="project__image"><img src="http://unsplash.it/600/400?image=7" width=600 height=400 alt=""></a>
  </div> 
</div> 
```
For the last part do every thing i say 
For the end we will put the details first we start with a div class name project__detail and then inside whe put a h2 with the class project__title and last we use the tag small with a class name project__category
```html
<div class="project">
  <div class="project__card">
    <a href="" class="project__image"><img src="http://unsplash.it/600/400?image=7" width=600 height=400 alt=""></a>
    <div class="project__detail">
    <h2 class="project__title"><a href="#">Project Name</a></h2>
    <small class="project__category"><a href="#">Photography</a></small>
    </div>
  </div> 
</div> 
```
