# jquery-svg-placeholder

A simple tool that helps with placeholder images when building a theme.

### Usage
    
    <!-- include jQuery and the placehold lib -->
    <script src="//ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js"></script>
    <script src="jquery.svg.placeholder.js"></script>


    <!-- Call the plugin -->
    <script type="text/javascript">
      $(function(){
        $('img[data-ph]').tsPlaceHold();
      })
    </script>
	
		
    <!-- start using placeholders -->
    <img data-ph="250:200" />
	
    <!-- 3rd option is text to be written in image -->
    <img data-ph="250:200:content" />