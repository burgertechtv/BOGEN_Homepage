Navbar (Menu)
	HTML
	1. Nav class(navbar, navbar-default)
		- Alle die HTML "menu" Elemente stehen drin.
		- Die Struktur des Menüs geht folgendermaßen: 
			
<nav> (navbar, navbar-default)
  |<div> (navbar header)
  |<button> (navbar-toggle) data-target="#links"
  |  |	- Hier liegt der Menubutton, der offnet die URL Menü  
  |  |	- Man verbintet das "data-target" Attribut von <button> mit dem richtigen Abschnitt 
  |  |		z.B. data-target="#links" -->  <ul id="links"> ***Links *** </ul>  
  | </button>  
  | <button> (navbar-toggle) data-target="#search"
  |  |	+ Hier liegt der Menubutton, der offnet die Suche Menü
  |  |	+ Man verbintet das "data-target" Attribut von <button> mit dem richtigen Abschnitt 
  |  |		z.B. data-target="#search" -->  <div id="links"> ***Links *** </div>
  |</button>
  |***BOGEN Logo Area***
  | <a> (navbar-brand)   
  |  |	<img id="logo_img" src="img/logo.jpg"> </img>
  |  |	- Die Große vom Logo wird in CSS Stylesheet mit "#logo_img" gesetzt.
  | </a>
  |*** Dropdown Menu Section | URL Links ***
  | <ul> (collapse, navbar-collapse, nav, navbar-nav) id="links"
  |  |<li> (dropdown) data-toggle="dropdown"
  |  |	| <a> (dopdown-toggle) data-toggle="dropdown" role="button"
  |  |  |  |   ***Top Level Dropdown***
  |  |  |  | Magnetic Measurement Solution
  |  |	| </a>
  |  |	| <ul> (collapse navbar-collapse, nav, navbar-nav) 
  |  |	|  | <ul> (dropdown-menu)
  |  |	|  |  | <li> <a href="#">Dropdown Link 1 </a> </li>
  |  |	|  |  | <li> <a href="#">Dropdown Link 2 </a> </li>
  |  |	|  | </ul>
  |  |	| </ul> 
  |  | </li>
  |  </ul>
  |*** Dropdown Menu Section | Search Function ***
  |<div> (collapse, navbar-collapse) id="search"
  |  | <form> (navbar-form navbar-right)
  |  | 	 |  <div> (form-group)
  |  |	 |    | <input> (form-control) ***Search Field***	
  |  |	 |  </div>				
  |  |	 |  <button> (btn, btn-default) 					
  |  |	 |     | <span> (glyphicon, glyphicon-search) </span>				    
  |  |	 |  </button>      
  |  | <form> 			  					
  | </div>
 <nav>
  
