# BCMagnet
BCMagnet Function ( No jQuery needed ) 
A very simple way to make your menu stick to the top on a scroll event.


BCMagnet function tracks top-edge of a target element and a scroll amount.
When top most edge of a target element hits the top of the screen, a class added.


*With this class you can stop element from scrolling off the screen and stick it to the top of the screen edge.


#1 Add link to magnet.js in html <head> element.
 Asuming you have magnet.js file downloaded and stored in 'js' directory. 
```
   <script type="text/javascript" src="js/magnet.js"></script>
```
#2 Add call function from HTML document

'There are different wasy to initiate code on pageloade. I decided to use this. Go whith what ever works for you.'
```
 document.addEventListener("DOMContentLoaded", function(event) {
    var targetElement = 'mainNav';
    var className = 'magnet';
    BCmagnet(targetElement,className);
 });
```

#3 Add css class to your style.css 
ClassName is up to you. Just make sure that you use the same class name when calling BCmagnet function
This class has to have something like this:
```
.magnet{
	position:fixed;
	top:0;	
}
```

