# Socialbox
Create yor social icon and link to you social media pages

The plugin requires jquery.

Add a div where you want to create social media icons


<div id='socialbox'> </div>

Add the script to invoke the social media at page load:

$(document).ready(function(e) { 
$("#socialbox").socialbox({
		facebook:"https://www.facebook.com/pages/Verticurl/131421280208994",
		twitter:"https://twitter.com/VertiCurl",
		linkedin:"https://www.linkedin.com/company/verticurl-pte-ltd"
		});
		
		});


Specify as "null", if you dont want to diaply any social media.

if yo want to hide the twitter, add null in the option as below

$(document).ready(function(e) {

    $("#socialbox").socialbox({
		facebook:"https://www.facebook.com/pages/Verticurl/131421280208994",
		twitter:null,
		linkedin:"https://www.linkedin.com/company/verticurl-pte-ltd"
		});
		
		});

I hope it will be helpful.
