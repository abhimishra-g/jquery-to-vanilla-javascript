# jquery-to-vanilla-javascript    
**Find Elements**    
**jquery**    
`$(".className")`   
**javascript**    
select the first instance of .className    
`document.querySelector(".className")`    
select all instances of .className    
`document.querySelectorAll(".className");`

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
 
