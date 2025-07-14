This is assignment 3 for the OntarioLearn course Python for Web Development hosted by Sheridan College.  

Assignment 3: HTML Django templates

User Name: jeremy pwd: Admin1234$  
User Name: instructor pwd: DjangoRocks1!


This assignment continues to build upon your blog project.

For this assignment, you are tasked to style your base template using CSS. You will create a look & feel that best suits your taste and the content of your site. The design portion is a creative exercise, but technical considerations covered in this module will be evaluated.

- Create a base template with at least one content block which is styled using CSS.
- Create a home page (view & template) which extend the base template
- Render the list of topics contained in the Topic model in a sidebar
- Include the total number of posts using for each topic (hint: use query annotations). You may display topics without posts – they will have a count of 0.
- Order the list by the most popular topic (most posts)
- Limit to top 10 posts
- Ensure that there is sample data in your site's database to appropriately render content.

Evaluation
Grading 	Criteria
- / 3 	Base template structure & design
- / 3 	At least one content block which is styled using CSS
- / 3 	Create a home page (view & template) which extend the base template
- / 3 	Render the list of topics
- / 3 	Ensure that there is sample data in your site's database to appropriately render content

Grade ( / 3 ) 	Explanation of the Criteria
- 3 	Criteria is met and all functionality is present
- 2 	Criteria is mostly met with some gaps in functionality
- 1 	Criteria is mostly unsatisfied or not functional, though some elements are present
- 0 	Criteria is not met. No visible attempt to satisfy it exists

Submission Details:

 - Submit in the assignment dropbox:

  - A copy of your db.sqlite3 file containing your database.
  - The GitHub repository URL
  - Create a superuser account for yourself and for the instructor. The instructor username should be: instructor and the password should be DjangoRocks1!

Running the code:
- The instructor will run your code using these steps. Make sure your project is compatible.
- Checkout your code from the provided public Github repository. 
- Install any new pip modules by running: pip install -r requirements.txt 
- Copy your db.sqlite3 submitted file to the project folder 
- Start the website: python manage.py runserver
- Test your website by navigating to: http://127.0.0.1:8000

**The course grading policy is available here: Evaluation Plan & Grading Policy.**