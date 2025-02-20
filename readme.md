TPS School Locator
======

The TPS School Locator is a tool used to search for and compare schools in the Tulsa Public School system.


>The CPS School Locator allows you to search for your neighborhood school, search for schools within a radius of an address, search for schools within a zip code, and search for schools close to your current location.

**How to use the CPS School Locator**
------
## Searches
There are four types of search results:

1. Address/Location
2. School
3. Radius
4. Zip Code

#### Address Search
**An Address Search results in your neighborhood school being shown.** If an address is typed into the search box the result lists the neighborhood schools (elementary, middle, and high) that your child can attend (without having to fill out an application). The map shows the geolocated address, the school locations, and the attendance boundary areas.

#### Location Search
**A Location Search results in your neighborhood school being shown.** If you press and hold on the map for 2 seconds or click the Find Schools Around Me button the display lists the neighborhood schools (elementary, middle, and high) that your child can attend (without having to fill out an application). The map shows the location of the long press (or the geolocated address of the Find Me feature), the school locations, and the attendance boundary areas.

#### School Search
**A School Search results in one school being displayed.** If a school name is typed and chosen from the drop-down the detail panel of that school is displayed. The map shows the school location and attendance boundary area.

#### Radius Search
**A Radius Search results in all the schools within a radius being displayed.** If you click the More Schools button the display lists all the schools within a 2 mile radius. The map shows the center of the radius and the school locations.

#### Zip Code Search
**A Zip Code Search results in all the schools within a zip code being displayed.** If a zip code is typed and chosen from the drop-down the display lists all of the schools located with that zip code. The map shows the school locations.

#### URL Lookup
**Pass in the school ID or your address in order to target one or more schools.** The URL should end with ?Schools=609720 or for multiple schools ?Schools=609720;609678. To view your neighborhood high, middle, and elementary school options, pass in ?Address=1234+N+Western+Chicago+IL+60622. Add &Type=HS or ES to return only high or elementary neighborhood schools. City, State and Zip are not required but should be added for more accurate results.

This example will return the neighborhood high school for a student residing at 1234 N Western. http://cps.edu/ScriptLibrary/Map-SchoolLocator/index.html?Address=1234+N+Western+Chicago+IL+60622&Type=HS

>To show all schools, click the Magnifying Glass when the input box is empty.

## Compare Schools
To compare metrics such as Number of Students, Rating, and Percentile Scores in Reading and Math click the box to the left of the school name in the display list. A panel at the bottom of the screen will show the checked schools.

>Click the down arrow on the panel to hide the Compare Schools Panel. Click the check box icon above the zoom buttons at the bottom left of the map to show the Compare Schools Panel.

## Filters
Filters can be applied to the results in order to narrow your search. You may have to click the "More Schools" button to get a list of schools within a radius. The results can be filtered by:

1. Grade Category
2. Performance Rating
3. School Classification
4. Programs Offered (coming soon)

## Overlays
An overlay is a transparent layer of additional information that appears on top of the existing map to help denote specific boundaries or regions. For example, a zip code overlay will show boundaries for all the zip codes in Chicago. The CPS School Locator includes the following overlays:

**School Boundaries**

1. [Elementary School Attendance](https://fusiontables.google.com/DataSource?docid=1nk2zVa4Nff9MlV5txIkjHbB_XXF0uaXXaVem6bf-#rows:id=1)
2. [Middle School Attendance](https://fusiontables.google.com/DataSource?docid=1zv2fI3v0CxkRIrn-AYujwXq1ljcq6uGOtyGYlN8F#rows:id=1)
3. [High School Attendance](https://fusiontables.google.com/DataSource?docid=1NXIcj0Eo65MNv-wczBoEMcovlsIJ1p66CfeP8JFV#rows:id=1)
4. [Charter School Preference Boundary](https://fusiontables.google.com/DataSource?docid=1VjPpibBwSQofLDVc9bJglve1shJnJ4aedwtJKNbZ#rows:id=1)
5. [Local School Council Boundary](https://fusiontables.google.com/DataSource?docid=12DTXu4VYBd7mW-2rBPlClAwXNMMuwnHSvSKRbsZe#rows:id=1)


**Geographic Overlays**

1. [CPS Networks](https://fusiontables.google.com/DataSource?docid=1pPqntpZutIHOGjrmgtQBmewcRPS9ylKB2UE6CsE#rows:id=1)
2. [Safe Passage Routes](https://fusiontables.google.com/DataSource?docid=12DTXu4VYBd7mW-2rBPlClAwXNMMuwnHSvSKRbsZe#rows:id=1)
3. [CPS Tiers](https://fusiontables.google.com/DataSource?docid=17dekfhiMcuMseVMI6qNIxhvtcOIb8RqsYfqgYyHg#rows:id=1)
4. [Community Areas](https://fusiontables.google.com/DataSource?docid=1uhe1AW1OkXnOUeG8GJHjv4HjlSQD860pRHI-iws#rows:id=1)
5. [Zip Codes](https://fusiontables.google.com/DataSource?docid=1uv4fLfrGKW52CJfOSFCiS8-H9ESqlRM1WB-XGgM#rows:id=1)
6. Transit
7. Bike Paths

**Political Overlays**

1. [Wards](https://fusiontables.google.com/DataSource?docid=1vKuFogOwwJ2YdXOVHLxbqy6Uc7ILpIbRePGK2GoD#rows:id=1)
2. [Illinois House District](https://fusiontables.google.com/DataSource?docid=1lvfheusomCd7Sh72GvFn23JVDQFhoNYQuUGI_JOQ#rows:id=1)
3. [Illinois Senate District](https://fusiontables.google.com/DataSource?docid=1H7my_qI1_hNeMuqUJcYhBUWzCjvdaJeBaiV6CkCk&pli=1#rows:id=1)
4. [US Congressional District](https://fusiontables.google.com/DataSource?docid=1xaQnriJ9YuF9wqj_lnk_OPVeOnYb4NEYMt-b71WO#rows:id=1)

## Features
 * Toggle between School Category and School Rating icons
 * Google Street View
 * Link to CPS School Profile
 * Directions by Google
 * Introductory tour
 * LSC Boundaries

**How to make a School Locator for your district**



## Dependencies
 * [Google Maps](https://developers.google.com/maps/documentation/javascript/)
 * [jQuery](http://jquery.com/)
 * [Hopscotch](https://github.com/linkedin/hopscotch)
 * [Bootstrap](http://getbootstrap.com/)
 * [FontAwesome](http://fontawesome.io/)


Copyright (c) 2019 Tulsa Public Schools. Released under the MIT License.
