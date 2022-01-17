React Router app created using guidelines and base files from Codecademy's React Router course. Base files saved in Base data folder.

Users can use the navigation bars to view different species of pets or search for a pet using the search feature.
Users can click on a pet to view their details. If the details are not avaiable, the user is directed to a page notifying them of so and are able to navigate back to their previous location.

App.js uses Router and Switch to control which component to render based on the URL
Navigation component uses NavLink component with activeClassName props to control the URL and change the style of the selected link
Search component uses useHistory and push to control the URL and direct the user to their search for pet
Pet Detals Not Found page uses useHistory to direct users back to their previous location
Pet Details page uses useParams to capture the type and id of a selected pet. The Redirect component is also used if a pet's details are not available
Search page uses useLocation to capture the search parameter.
Home page uses the Link component to control the URL and allow Route components to function
