# Milestone Project 2 - Dan's City Breaks

Dan's City Breaks provides an interactive, practical, meaningful and helpful user experience for anyone looking to take a city break across several global locations. 
Together with our network of partners located around the world, we have carefully selected only the best and most popular countries to visit. 
Cities are made available to view via the Google Maps window, with hotels and areas of interest available to select via our Application which
 can be accessed through the user's web browser and other platforms.

The Google Maps window provides a very 'real' context through which the user can get a sense of exactly where they will be staying. 
By first selecting the country of their choice, the user then needs to free-type a city of their own interest. 
Once the user starts to free-type their preferred city location in the data field, the Application auto populates helping to ensure 
the user completes that data field correctly. 
The Application then offers hotel options via the Google Maps window. 
This information is also presented in a table format immediately below the Google Map.  

This project is hosted through GitHub Pages. 
Please click on this link to view: [Dan's City Breaks](https://tenerim.github.io/Milestone-2/).

# UX
I designed the Application with the experienced traveler in mind - someone who is already familiar with travel, and who is looking for an easy way to finding hotel 
options, with things to do in a local area during a city break. 
At the same time, I wanted to ensure it was user friendly enough for someone not so experienced in searching for city breaks.

Specific User Stories for this project are:

* As a site user:
  - Easily and quickly select a number of country locations as options / places to visit
  - To be able to choose from a number of hotels in an area the user is interested in traveling to
  - To identify various things to do and places to go in that city
  - To be able to connect directly with someone from the Dan's City Breaks website to discuss options and ask questions directly if necessary

* As a site owner: 
  - Provide a user-friendly Application that helps users to decide where to travel for their city break 
  - Make optimal use of the Google Maps API and the functionality available to site owners and to users  

I used [balsamiq](https://balsamiq.com/) to design my mock-ups. These provide the insight and logic into the design and purpose of the Application. Please click on the following link to view the 
mock-ups: [mock-ups](https://github.com/tenerim/Milestone-2/tree/master/assets/MockUps).

1. The opening page provides the user with an immediate and simple view with instructions on what the user needs to do to
 'choose from a wide selection of popular city locations'.
2. Page 2 offers a list of the hotel options available to the user - this assumes the user is already familiar with the 
area and may prefer to select from the drop-down list, rather than search for any one hotel from the map window.
3. Page 3 offers several direct contact options from around the world, along with Social Links, providing the user with 
options to contact a representative from Dan’s City Breaks.


# Features
The primary purpose of the Application is to allow the user to select country options from a set list of available countries for city breaks, while helping them to then select city options 
through a separate free-type data field. The availability of the Google Maps window and the ease with which the user can view the geographic location 
of each city via that window, is a particularly strong feature of the project. Once a hotel has been selected, the user is then provided with another layer of 
information with regards to the amenities surrounding the hotel, and within their city of choice.   

Specific features of the Application are noted immediately below: 
1. The drop-down data field allows the user to choose from a select number of country options immediately above the Google Maps window.
2. The free-type data field auto-populates with the city options available for the selected country. 
3. A complete list of hotel options appears within the Google Map window from where the user can select a specific hotel by clicking on the hotel pin. 
4. That same list appears in a table format below the Google Maps window, which can be used by the user as an alternative method for selecting their hotel of choice. 
5. A pop-up bubble appears within Google Maps once the user has selected a particular hotel. This pop-up includes the following information:  
name of the hotel; the address and contact number for the hotel; a link to the hotel website; and the hotel rating. 
6. Clicking on the name of the hotel takes the user to a more detailed Google Maps page, with additional features and options including: 
    - Hotel availability and pricing in a separate browser panel
    - Local information for the area immediately surrounding the hotel, also in the separate panel
    - An area map of the city within the main browser window including key amenities and attractions 

## Additional (future) features might include:
* Links to additional sites that offer package deals, flight information and car hire options for the location selected
* All country options would be made available and displayed by continent 
* A drop-down list of a limited number of preferred cities selected by Dan's City Breaks - this would be in addition to the city free-type field which would remain
* Fully functioning Social Links which (for the moment) tie back to the Application page only 
* User feedback from people who have used the site previously

# Technologies Used
* [html](https://en.wikipedia.org/wiki/HTML) 
  - the base language used to build the web-site
* [css3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) 
  - to simplify the format and layout of the web pages by enhancing the code in the html pages 
* [jQuery](https://jquery.com/)
  - to simplify DOM manipulation and interact with the Google Maps API
* [Bootstrap](https://getbootstrap.com/)
  - to use ready-made design templates to enhance the front-end appearance and user-experience of the web-site 
* [font-awesome](https://cdnjs.com/libraries/font-awesome)
  - selected from the cdnjs libraries to support the 'Social' links in the footer of the Application
* [Google Maps Platform](https://developers.google.com/maps/documentation/javascript/examples/places-autocomplete-hotelsearch?hl=es-419)
  - selected for the Google Maps Javascript API with autocomplete Hotel Search functionality

# Testing
Multiple tests were completed to support the Application. Details of Manual testing, User Story testing, and Process testing 
are document below.

In addition, a table containing the results of tests completed across various criteria can be found in the following
 [link](https://github.com/tenerim/Milestone-2/blob/master/assets/Testing/Testing.JPG). 

External mark up validation services were also used to test the integrity of html and css code. 

* The following tests were manual, specifically:  
  - Each page was reloaded every time a new section was completed
  - The Application was then reviewed in all available mobile views
  - Any errors or inconsistencies were corrected by adjusting for the column widths within each container
  - This also ensured the text aligned appropriately for the screen size chosen
  - All images are coded to fit the full width of the screen on any mobile device and to sit side-by-side on a larger device
  - The Social links in the footer tie back to the Application page (as currently intended) and the colour of each changes as appropriate when hovered over.

* User Story Testing for the User: 
  - The user can quickly and easily select from several country locations and choose from various hotels in an area they are interested in traveling to
  - Various facilities and ideas for things to do are available in the Google Maps window once the user selects a specific city 
  - More specific detail is made available once the user selects a specific hotel to view
  - Contact information is included for the four offices in which Dan's City Breaks operates so the user can connect with a live representative as appropriate

* User Story Testing for the Owner: 
  - The application provides the information that can help users to decide where to travel for their city break
  - While several alternative API's are available via Google Maps, I believe optimal use is made of this particular API

* The following scenario describes the manual testing process for the central feature of the Application - the selection of the country and city locations: 
  1. Click in the Country Location drop-down list to select a preferred country - the Google Map image will change accordingly.
  2. Free-type a preferred city for that country in the City Location data field - this field will auto-populate.
  3. Pins will drop onto the map to identify hotels in that city - the user can select from within the map itself or from the list of hotels that are then made available beneath the Map.
  4. Once any hotel is selected a pop-up will appear for that hotel displaying the name, address, contact information and Hotel Rating, in addition to the hotel's direct web link.
  5. Select the hotel name to be taken directly to a closer view of the local area. On this page: 
      - Local facilities immediately surrounding the hotel will appear and the user will be to view and select these as preferred
      - A separate panel displays more information about the hotel
      - A hotel booking can be made directly from that panel 
      - Alternative hotel options are also listed for user reference

* The following web sites were used to validate my code: 

  - [W3C-HTML](https://validator.w3.org/) to test and validate my html file 
  - [W3C-CSS](https://jigsaw.w3.org/css-validator/#validate_by_input) to test and validate my css file

# Deployment
Dan's City Breaks was developed on GitPod, with the repository hosted on GitHub and GitHub Pages.

## To deploy the project using GitHub Pages:
1. Navigate to the project via the following link: https://github.com/tenerim/Milestone-2.
2. In the navigation bar select the last option available ('settings').
3. Scroll down to the GitHub pages area.
4. Select 'Master Branch' from the 'Source' dropdown menu.
5. Select the option titled 'master branch - Use the master branch for GitHub Pages'.
6. The project should now be available via GitHub Pages. 

There are no differences between the deployed version and the development version. 

## To deploy the project locally:
1. Navigate to the project via the following link: https://github.com/tenerim/Milestone-2.
2. Click the green 'Clone or Download' button. 
3. Copy the URL that appears in the drop-down box. 
4. Paste the URL into any locally preferred IDE platform. 
5. The project will now be available via the local platform.  

# Credits
* Content
  - The content for the footer section was taken from the footer of the [My Resume](https://github.com/tenerim/resume) project, completed during the User Centric Frontend Development Module of the Course. 
* Media
  - The photos used in this site were obtained from [Coverr](https://coverr.co/search?q=city).
* Acknowledgements
  - I received inspiration for this project from my family with support and coaching provided by my Mentor [Precious Ijege](https://github.com/precious-ijege/).
