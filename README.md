# jquery.mobile-scroll
A jquery plugin to simulate mobile scrollbar on pc.

## Demo
HTML code:
```html
<style>
.scroll-bar { position:fixed; right:0px; top:0px; width:10px; background:transparent; z-index:99999; overflow:hidden; }
.scroll-bar .handle { position:absolute; left:0px; width:8px; border-radius:10px; overflow:hidden; background:rgba(0,0,0,0.4); cursor:pointer; }
</style>

<div class="scroll-bar"><b class="handle"></b></div>
```

JS Code:
```javascript
 $(".scroll-bar").mobileScroll();
```

## Options
###1.autohide (default:true) 

  auto show/hide for wheel event or mouseover/out on screen edge. 
  
###2.wheelctl (default:true) 

  add listener for mouse wheel event. 
  
###3.mousectl (default:true) 

  add listener for mouse drag event. 
  


