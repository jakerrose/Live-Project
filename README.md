# Live-Project
## MVC Web App for Theatre Vertigo Using Entity Framework and .NET Framework

    The Tech Academy's Live Project was a collaborative project that emulates the job environment with other students and instructors and was a great way to get
    hands on experience. We created a working MVC 5 web app using agile and SCRUM methodologies. 
    The project consisted of a two week long sprint with daily standups where the
    team would plan for the day and share any roadblocks and week-end code retrospectives where we would reflect on the project and what went well and what could be improved.
    The project was managed through Azure DevOpa with source control through Azure and Visual Studio 2019 and team communication through Discourse. 
    I was assigned stories and worked on them in VS with each story assigned to a separate branch. 
    When the code was approved, I pushed the code through VS to Azure where I would create a pull request.

   # COMPLETED STORIES
        
	* Create and Style About Page

    I used a visual mockup of a design to create the About page. I created a new View then used CSS and HTML to create the front-end design of the page.

	* Create entity model for Rental History and CRUD pages

    In this story, I created an entity model for the RentalHistory class so it could be saved to a database. 
    I used a model first approach by adding a class to the Rent area Models, typed out the properties, and then adding a New Scaffold Item to let Entity Framework take care of the scaffolding.

	* Rental History CRUD Part #1: Create & Edit Page

    For this assignment I edited the text and styled the Create Rental History page which involved using css to create a container with a red background, center the text, and create two 		colored     buttons.
    I used JQuery to change the text on an input field from Notes to Damages Incurred when the checkmark was checked and unchecked using a toggle function that relied on boolean logic.

	* Rental History CRUD Part #2: Index Page

    I created a stylized table of rental histories using Font Awesome for X and checkbox icons, a dropdown which also included icons inside, and an ellipsis icon that
    appears on hover to reveal the dropdown. To hide the ellipsis and show on hover, I used the jQuery .hide() function and the .show() and .hover() functions to show the content when hovering 	        over any cell with the mouse. 
    The result is a rental history page with the option of editing each row, deleting, or viewing more details with the dropdown.
