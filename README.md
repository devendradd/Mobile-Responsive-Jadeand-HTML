# Mobile-Responsive-Jadeand-HTML


use following code for jade file

doctype html
html
  head
    title= title
    script(type='text/javascript' src='https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js')
    script(type='text/javascript' src='//cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.4/js/bootstrap.min.js')
    script(type='text/javascript' src='/javascripts/search.js')
    link(rel='stylesheet', href='/stylesheets/style.css')
    link(rel='stylesheet', href='bootstrap.css')

  body
    nav.navbar.navbar-default(role='navigation')
      .navbar-header
        button.navbar-toggle(type='button', data-toggle='collapse', data-target='#example-navbar-collapse')
          span.sr-only Toggle navigation
          span.icon-bar
          span.icon-bar
          span.icon-bar
        a.navbar-brand(href='#') TutorialsPoint
      #example-navbar-collapse.collapse.navbar-collapse
        ul.nav.navbar-nav
          li.active
            a(href='#') iOS
          li
            a(href='#') SVN
          li.dropdown
            a.dropdown-toggle(href='#', data-toggle='dropdown')
              | Java
              b.caret
            ul.dropdown-menu
              li
                a(href='#') jmeter
              li
                a(href='#') EJB
              li
                a(href='#') Jasper Report
              li.divider
              li
                a(href='#') Separated link
              li.divider
              li
                a(href='#') One more separated link
                
                
      -------------------------------------------------------------------------------          
                
                
 use below code for HTML mobile responsive
 <nav class = "navbar navbar-default" role = "navigation">
   
   <div class = "navbar-header">
      <button type = "button" class = "navbar-toggle" 
         data-toggle = "collapse" data-target = "#example-navbar-collapse">
         <span class = "sr-only">Toggle navigation</span>
         <span class = "icon-bar"></span>
         <span class = "icon-bar"></span>
         <span class = "icon-bar"></span>
      </button>
		
      <a class = "navbar-brand" href = "#">TutorialsPoint</a>
   </div>
   
   <div class = "collapse navbar-collapse" id = "example-navbar-collapse">
	
      <ul class = "nav navbar-nav">
         <li class = "active"><a href = "#">iOS</a></li>
         <li><a href = "#">SVN</a></li>
			
         <li class = "dropdown">
            <a href = "#" class = "dropdown-toggle" data-toggle = "dropdown">
               Java 
               <b class = "caret"></b>
            </a>
            
            <ul class = "dropdown-menu">
               <li><a href = "#">jmeter</a></li>
               <li><a href = "#">EJB</a></li>
               <li><a href = "#">Jasper Report</a></li>
               
               <li class = "divider"></li>
               <li><a href = "#">Separated link</a></li>
               
               <li class = "divider"></li>
               <li><a href = "#">One more separated link</a></li>
            </ul>
            
         </li>
			
      </ul>
   </div>
   
</nav>



------------------------Html with responsive navigation and dropdown emedded with bootstrap-------------------

