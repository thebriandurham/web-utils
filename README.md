# web-utils
IDK web utils man

## getloc.html
Simple web page that uses IP geolocation to show your current IP address, your geolocation (city and country), and the current date and time in both your local timezone and UTC.

It's a basic POC at this point. Eventually will set up my own express API to provide the IP and geoloc data without relying on third party APIs

### Technologies Used
- HTML
- CSS
- JavaScript
- Leaflet.js for the map display
- IPify API for fetching the IP address
- IPapi for fetching the geolocation based on the IP address

### Setup and Usage
- Clone this repository to your local machine.
- Open the index.html file in your browser.
- The page will automatically fetch your IP address, geolocation, and current date/time, and display them on the page.
- Host it on your web host so you don't have to rely on sketchy 'whatismyip' sites
