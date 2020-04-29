# Project Name: 
Milestone Project 2 - Dan's City Breaks

Dan's City Breaks provides an interactive, practal, meaningful and helpful user experience for anyone looking to take a City Break across a number 
of global locations. Together with our network of partners located around the world, we've carefully selected only the best and most popular countries to visit. 
We've then identified cities where our users could choose to say, with hotels and areas of interest all available to view and to select via our 
Application which is available through the user's web browser, and other platforms.

The Google Maps window provides a very 'real' context through which the user can get a sense of exactly where they'll be staying. By first selecting the
country of their choice, they'll then need to free-type a City of their own particular interest. Once the user starts to free-type their preferred City location
in the City input field, the Application offers the user some options they might not have considered, while also helping ensure the user completes that data field 
correctly. The Application then offers hotel options via the map window, and also via a full list of available hotels immediately below the Google Maps window.  

<!---Is this ok to use as the link to the live project?---->
This project is hosted through GitHub Pages: https://tenerim.github.io/Milestone-2/ 

# UX
I designed the web site with the experienced traveler in mind - someone who is already familiar with travel, and is looking for an easy way to finding hotel 
options, with things to do in a local area during a City break. 

Specific User Stories for this project are:

* As a site user:
  - Easily and quickly select a number of Country locations as options / places to visit
  - To be able to choose from a number of hotels in an area they are interested in traveling to
  - To identify various things to do and places to go in that City
  - To be able to connect directly with someone from the Dan's City Breaks web-site to discuss options and ask questions directly with somoene if necessary

* As a site owner: 
  - Provide a user-friendly web-site that helps users to decide where to travel for their City Break 
  - Make optimal use of the Google Maps API and the functionality available to site owners and to users  

The following wireframes provide the insight and logic into the design and purpose of the site [mock-ups](https://github.com/tenerim/Milestone-2/blob/d78928c34db959f0c286267eb92c5f9d5eabdf15/assets/Wireframes)

1. The opening page is simple yet informative. It provides the user with an immediate and simple view with instructions on what 
  the user needs to do to 'choose from a wide selection of popular City locations'.
2. Page 2 offers a list of the hotel options available to the user - this assumes the user is already familiar with the area and might prefer to 
  select from the drop-down list, rather than search for any one particular hotel from the map window in Page 1. 
3. Page 3 offers a number of direct contact options from around the world, along with Social Links, providing the user with options to contact a representative
  of Dan's City Breaks directly. 

# Features
<!-----An opening paragraph with context has been added here, and the features re-worked-------->

* The primary purpose of the site is to allow the user to select country options for city breaks while helping them to then select city options 
through a separate free-type data field. The availability of the Google Maps window and the ease with which the user can view the georgraphic location 
of each city via that window is a particularly strong feature of the project. Once a hotel has been selected, the user is then provided with another layer of 
information with regards to the amenities surrounding the hotel (and within their city of choice).   

More specific features are that the Application: 
1. The drop-down data field allows the user to choose from a select number of country options immediately above the Google Maps window.
2. The free-type data field auto-populates with the city options available for the country they've selected. 
3. A complete list of hotel options appears within the Google Map window from where the user can select a specific hotel by clicking
on the hotel pin. 
4. That same list appears in a table format below the Google Maps window, which can be used by the user as an alternative method for selecting 
their hotel of choice. 
5. A pop-up bubble appears within Google Maps once the use has selected a particular hotel. This pop-up includes key information such as the 
name of the hotel, the address, a contact number, a link to the hotel website, and the hotel rating. 
6. Clicking on the name of the hotel takes the user to a more detailed Google Maps page, with additonal features / options including: 
  - Hotel availability and pricing options in the left browser panel
  - Local area information regarding the area immediately surrounding the hotel, also in the left browser panel
  - An area map wihtin the main browser window of the city and key amenities / attractions 

## Additional (future) features might include:
* Links to additonal sites that offer package deals, flight information and car hire for the location selected
* Additional country and City options by continent 
* User feedback from people who have used the site and found it useful 
* A limited drop-down list of Cities in addition to the City free-type field, should people not have a specific City location already in mind
* Fully functioning Social Links which (for the moment) tie back to the Application page only 

<!-----------Technologies Used has been updated------>

# Technologies Used
* [html](https://en.wikipedia.org/wiki/HTML) 
  - the base language used to build the web-site
* [css3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) 
  - to simplify the format and layout of the web pages by enhancing the code in the html pages 
* [jQuery](https://jquery.com/)
  - to simplify DOM manipulation and interact with the Google Maps API
* [Bootstrap](https://getbootstrap.com/)
  - To use ready-made design templates to enhance the front-end appearance and user-experience of the web-site 
* [font-awesome](https://cdnjs.com/libraries/font-awesome)
  - Selected from the cdnjs libraries to support the 'Social' links in the footer of the Application 

# Testing
* The following web sites were used to validate my code: 
  - [W3C-HTML](https://validator.w3.org/) to test and validate my html file 
<!----------Would be great if we could take a look at this together------->
  - [W3C-CSS] https://jigsaw.w3.org/css-validator/#validate_by_input to test and validate by css file
<!--------Can I test my JS code anywhere?---------->
<!--------How can I use Jasmine (if at all) to test my code?------> 

* The following tests were manual, specifically:  
  - I reloaded each page once I completed a new section.
  - Once I was confident with that view, I opened the page in the browser and ran the page in that view. 
  - The four 'local offices' have telephone numbers and web addresses intentionally left blank. 
  - I tested my website on the different scren sizes where I was able to correct any errors or inconsistencies by adjusting for the column widths within each container.
  - This also ensured the text aligned appropriately for the screen size chosen. 
  - On a smaller screen size the Google Maps window and the picture of Venice sit on top of each other - ensuring the user is still able to 
  see a full screen size of the map on their device. 
  - All images are coded to fit the full width of the screen on any mobile device, and to sit side-by-side on a larger device. 
  - The Social links in the footer tie back to the Application page (as currently intended) and the colour of each changes as appropriate when hovered over.

* User Story Testing for the User: 
  - The user is able to quickly and easily select from a number of country locations, and is able to choose from various hotels
  in an area they are interested in traveling to
  - Various facilities and ideas for things to do are available in the Google Maps window once the user selects a specific city. More specific detail
  is made available once the user selects a specific hotel to view
  - The ability to connect with a live representative from Dan's City Breaks is not made available 

* User Story Testing for the Owner: 
  - The application does provide the information that can help users to decide where to travel, for their city break
  - While a number of alternative API's are available via Google Maps I believe optimal use is made of this particular API

* The following scenario describes the manual testing process for the central feature of the Applicaiton - selecting the Country and City locations: 
  1. Click in the Country Location drop-down list to select a preferred country -> the Google Map will change accordingly
  2. Free type a preferred city for that country the the City Location data field -> this field will auto-populate
  3. Pins will drop onto the map to identify hotels in that city -> Select from within the map istelf, or from the list of hotels 
  made available beneath the image of Venice
  4. Once any hotel is selected, a pop-up will appear for that hotel, displaying the name, address, contact information and Hotel Rating, 
  in addition to the hotel's direct web link
  5. Select the hotel name to be taken directly to a closer view of the local area. On this page: 
      - Local facilities are easy to view and select
      - The left-hand panel displays more information about the hotel
      - A booking can be made directly from the left-hand panel
      - Alternative hotel options are also listed for user reference

# Deployment
This project is hosted through GitHub Pages: https://tenerim.github.io/Milestone-2/ 

<!--------Process I followed to deploy the project to a hosting platform?----------> 

All code is saved to the following repository in GitHub: https://github.com/tenerim/Milestone-2 

There are no differences between the deployed version and the development version. 

<!--------Should I explain how to run the code locally?----------> 

# Credits
* Footer
The content for this section was taken from the footer of the 'My Resume' project (the 'Mini Project with Bootstrap 4')
* Media
The photos used in this site, includeing the backdrop of the Golden Gate Bridge, were obtained from: https://coverr.co/search?q=city
* Icons
The icons used in this site were taken from fontawesome.com 
* Acknowledgements
I received inspiration for this project from my family, with support and coaching provided by Precious Ijege. 