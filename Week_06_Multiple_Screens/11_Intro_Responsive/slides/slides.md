![GeneralAssemb.ly](https://github.com/generalassembly/ga-ruby-on-rails-for-devs/raw/master/images/ga.png "GeneralAssemb.ly")

#FEWD - Lesson Name 

###Instructor Name

Instructors current role.

---


##Agenda

*	

---


<section data-background="images/ENTER IMAGE">

</section>

#Advanced Layout

---

![GeneralAssemb.ly](../../../assets/ICL_icons/code_demo_icon_md.png)
##Advanced Layout Discussion Activity

---


##Fixed Layout

*	Used up to this point

*	Relies on a container of fixed width

*	Usually 960px or 980px


<aside class="notes">

</aside>

---

##Responsive

*	Different styles for different screen widths

*	Uses an elastic/fluid layout

*	Fluid

*	Sized in percentages

*	Elastic

*	Sized in ems




<aside class="notes">

</aside>

---


##Fixed vs Responsive

Checkout these __Fixed__ sites

*	[UPS.com](http://www.ups.com)

*	[Boston.com](http://www.boston.com)

*	[Google.com](http://www.google.com)

*	[Getaround.com](http://www.getaround.com)


Checkout these __Responsive__ Sites

*	[Generalassemb.ly](http://www.generalassemb.ly)

*	[Dwolla.com](http://www.dwolla.com)

*	[Sweethatclub.com](http://www.sweethatclub.com)

*	[Relayrides.com](http://www.relayrides.com)

---



![GeneralAssemb.ly](../../../assets/ICL_icons/Exercise_icon_md.png)
##Boxing 1

---

##EMS vs REMs - Needs more clarity

__EM__
Sized based on the width of the letter “m” 
Same as percentages*
1em=100% font-size
http://alistapart.com/articles/howtosizetextincss
Based on parent
Parent{ font-size:16px;}
Child{font-size:2em;}
Child’s font size is 32px

__REM__

“Root” em
Same as em
Caveat: Based on the font-size of html element


<aside class="notes">
Some browsers have issues with fonts sized in percents

</aside>

---

![GeneralAssemb.ly](../../../assets/ICL_icons/Exercise_icon_md.png)
##Boxing con't

---


<section data-background="images/ENTER IMAGE">

</section>

#Media Queries

---

##Media Queries - what should be in code?

@media only screen and
(max-width: xPx)
(min-width: xPx)
(max-device-width:xPx)
(min-device-width:xPx)

For iPad
(orientation: portrait)
(orientation: landscape)

Separate multiple clauses with “and”


<aside class="notes">

</aside>

---

##Mobile Display

<meta name="viewport" content="width=device-width, initial-scale=1">
Optional: user-scalable=none

<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=none">



Why necessary?
Mobile browser assumption of fixed layout of 980px
Standard media queries sizes
Small: up to 768px
Medium: 768-991px
Large: 992px+

<aside class="notes">

</aside>

---

##Usage

/*float boxes into columns*/
.box{
	float:left;
}
@media only screen and (max-width:768px){
	/*insert responsive css here
	ex: stack floated boxes
	*/
	.box{
		float:none;
	}
} 

If I put the media query before .box{float:left;} will this work as expected?


<aside class="notes">

</aside>

---

![GeneralAssemb.ly](../../../assets/ICL_icons/Exercise_icon_md.png)
##Boxing Media Queries

---


##Optional

Grid layouts
Transition (make media query changes smoother)

<aside class="notes">

</aside>

---

##Topic


<aside class="notes">

</aside>

---

##Topic


<aside class="notes">

</aside>

---

##Topic


<aside class="notes">

</aside>

---

##Topic


<aside class="notes">

</aside>

---

##Topic


<aside class="notes">

</aside>

---

![GeneralAssemb.ly](../../../assets/ICL_icons/code_demo_icon_md.png)
##Code Demo

---


![GeneralAssemb.ly](../../../assets/ICL_icons/Exercise_icon_md.png)
##Exercises

---

## Homework

*	Review command line and GitHub.
*	Create your first blog entry.

---