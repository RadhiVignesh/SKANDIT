# SKANDIT
.sublinks li {
	border-bottom: 2px solid #007a78;
	padding:10px 5px;
}

.sublinks li:hover {
	background-color: #f2c75c;
}

.sublinks li::marker{
	content:"";
}

.sublinks li::after{
	text-align: center;
  float:right;
	font-family: 'etModules';
  content: "\3d";
	background-color: #007a78;
	width:25px;
	color:#ffc845;
	border-radius:15px;
}

#et-top-navigation{
	background-color:#800080;
	width:100%;
	padding-top:15px;
}
.et_menu_container{
	padding-left:0px !important;
	padding-right:0px !important;
}

.mm-f-families > a:first-child::after{
	content: "Making sure you're in control with our tailored support" !important;
}

.mm-f-needs > a:first-child::after{
	content: "A supporting partner for people with complex needs." !important;
}

.mm-f-location > a:first-child::after{
	content: "Search for your local PCS support." !important;
}

.mm-p-support > a:first-child::after{
	content: "Assurance for professionals." !important;
}

.mm-p-needs > a:first-child::after{
	content: "A supporting partner for people with complex needs." !important;
}

.mm-p-location > a:first-child::after{
	content: "Search for local PCS support centers." !important;
}

.mega-menu .menu-item-has-children > a:first-child{
	height:50px !important;
}

@media only screen and (max-width: 600px) {
.mega-menu .menu-item-has-children > a:first-child{
	height:auto !important;
}
	
	#et-top-navigation{
	background-color:white!important;
	width:100%;
	padding-top:10px;
}
	
}

@media only screen and (max-width: 800px) {
	
	#et-top-navigation{
	background-color:white!important;
	width:100%;
	padding-top:10px;
}
	
}
.mega-menu .menu-item-has-children > a:first-child::after{
	display:absolute;
	font-family:'Raleway',Helvetica,Arial,Lucida,sans-serif !important;
	font-size: 12px !important;
	font-weight:400 !important;
	text-align:left;
	left:30px !important;
	top: 25px !important;
	display:block !important;
}

.mega-menu .sub-menu .sub-menu li a {
	font-weight:500 !important;
	font-size: 14px !important;
}
.menu_cta {
background-color: #ffffff;
color: #000000;
padding: 0 !important;
margin-bottom: 15px !important;
border-radius:6px;
}

.menu_cta a {
color: #000000 !important;
padding: 15px 15px 15px 15px !important;
}
