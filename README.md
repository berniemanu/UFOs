# UFOs

## Project Overview
Dana needed my help to build webpage with dynamic table. As an enhanced feature in her webpage, she also wanted to provide a more in-depth analysis of UFO sightings to users by allowing them to filter for multiple criteria at the same time. The project was to enable users to filter for the city, state, country and shape.

## Resources
Data Source: UFO data
Software: HTML/CSS, JavaScript, Visual Studio Code 1.69.1, BootStrap 4.0.0

## Search Criteria Procedure
### Index page
This is the initial page. The user can re-initialize the page by clicking on the navbar at the top.
![image](https://user-images.githubusercontent.com/104685001/179957688-d9b191f3-5b6a-4a70-89a9-00ae9467b54d.png)

Filtering by event date
The user enters the desired date, the change is detected and the table is updated accordingly.
![image](https://user-images.githubusercontent.com/104685001/179957787-35a237e4-271e-4d55-806f-b9e135d691b6.png)

Filtering by city
The user enters the desired city, the change is detected and the table is updated accordingly.
![image](https://user-images.githubusercontent.com/104685001/179957870-8227c081-37ab-40e7-8b35-4af58c12665e.png)

Filtering by country
The user enters the desired country, the change is detected and the table is updated accordingly.
![image](https://user-images.githubusercontent.com/104685001/179957944-3ad545bb-c2e4-42a3-81bc-034cda1bf826.png)

Filtering by state and shape
The user enters the desired state and shape observed, the changes are detected and the table is updated accordingly.
![image](https://user-images.githubusercontent.com/104685001/179958099-e6047fcf-863a-443d-a477-dedbed835887.png)

Summary
Although more than 1 parameters can be entered simultaneously, major drawback of this design is the difficulty for the user to know what parameter to use for the filtering. However this can be easily rectified by:
* Drop-down lists including all filter values in place of the input fields.
* Automatic update of each list after a parameter is selected in any filter.
* A button below the filters to clear the filters.
