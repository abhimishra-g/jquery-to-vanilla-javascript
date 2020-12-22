# jquery-to-vanilla-javascript    
**Find Elements**    
**jquery**    
`$(".className")`   
`$("#id")`    
**javascript**    
select the first instance of .className    
`document.querySelector(".className")`    
select all instances of .className    
`document.querySelectorAll(".className");`    
select the elment with the specified ID    
`document.getElementById("id")`    

**Find One Element Within Another Element**    
**jquery**    
`$(".classNameParent").find(".classNameChild")`   
**javascript**    
`let container = document.querySelector(".classNameParent")`    
`container.querySelector(".classNameChild")`    

**Add Class**    
**jquery**    
`$(".className").addClass(".anotherClassName")`   
**javascript**    
`document.querySelector(".className").classList.add("anotherClassName")`    
 
**Remove an element from the page**    
**jquery**    
`var $elem = $(".className")`    
`$elem.remove()`    
**javascript**    
`var elem = document.querySelector(".className")`    
`elem.remove()`    
