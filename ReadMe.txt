Web Application that uses weather data from OpenWeatherMaps in JSON format to display current and forecasted weather. Options to view pressure, humidity and wind details.


Have named my html page 'forecast.html'.
On opening the page there is a short description and a simple form included in the div 'container'. The googlemap which focuses on Dublin is displayed on the left.
Simple form found in forecast.html (line 41 -54)
Submit	button - line 54
Checkboxes for Pressure, Humidity and Wind	speed located on lines (50,51,52)
By clicking	on the day number in the first column of the daily data a more detailed summary is provided. I could only get the more detailed data to reutrn based on the value initially selected in the dropdown menu. I assigned the button to a variable and gave it an increasing value (i+1) but could not access the variable outside the funciton. i.e. to use it within another funciton. I tried window.variable name and this didn't work. I also tried nesting the funciton inside the first function and this didn't work either.

	
Error	handling: originally when I selected a new day the more details would not disappear. I added in an extra funciton to close the div on click of the submit button. When 0 days are selected from the dropdown an error message is displayed. The user can close the table using the buttons at the botton. 
