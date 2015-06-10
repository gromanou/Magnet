# Magnet
Magnet Function ( No jQuery needed ) 

Magnet function tracks top-edge of a target element and a scroll amount.
When top most edge of a target element hits the top of the screen, a class added.

*With this class you can stop element from scrolling off the screen and stick it to the top of the screen edge.

#1 Add link to magnet.js in html <head> element.
 <script type="text/javascript" src="/js/magnet.js"></script>

#2 Add call function from HTML document

'There are different wasy to initiate code on pageloade. I decided to use this. Go whith what ever works for you.'

 document.addEventListener("DOMContentLoaded", function(event) {
    var targetElement = 'mainNav';
    var className = 'magnet';
    BCmagnet(targetElement,className);
 });
