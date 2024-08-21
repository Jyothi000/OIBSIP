HTML Structure:

  >>The HTML file (index.html) defines the structure of the web page. It includes:
  >>The <head> section with the page title, CSS links, and Font Awesome icons
  >>The <body> section with the main content of the page
  >>The <script> section at the end of the body, which contains the JavaScript code for the temperature conversion

The main content is divided into several sections:

The header with the title "Temperature Converter" and a temperature icon.
The text symbols for Celsius (°C) and Fahrenheit (°F), along with a weather icon.
The input fields for Celsius and Fahrenheit temperatures.


CSS Styling

>>The CSS file (style.css) defines the visual appearance of the web page.
>>It includes:e for the primary color (--primary-color)
Styles for the body, centering the content vertically and horizontally
Styles for the main container, including its size, border radius, background color, and box shadow
Specific styles for the header, text symbols, input fields, and icons.
The CSS also includes media queries for responsive design, adjusting the layout for smaller screens.


JavaScript Functionality:

The JavaScript code is embedded within the <script> tags at the end of the HTML file. It adds interactivity to the temperature converter:
>>It selects the Celsius and Fahrenheit input fields using their respective IDs.
It adds event listeners to the input fields, listening for the "input" event (when the user types or changes the value).
>>When an input field value changes, the code calculates the corresponding value in the other scale using the appropriate formula (°C to °F or °F to °C).
>>The calculated value is then displayed in the corresponding input field.
>>The code ensures that the displayed values are rounded to four decimal places if the result is not an integer.

Summary:
Overall, this code creates a simple and user-friendly temperature converter that allows users to easily convert between Celsius and Fahrenheit temperature.



# Oasis-Infobyte
