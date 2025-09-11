Colin Lemire - Assignment 2


## To-do List Application
The program I made is a very simple to-do list. It starts with 3 deletable items displayed in a field that are examples of tasks that I actually did need to do in real life. Other than that, there is a form that can be filled out where the fields are clearly labeled: Task (where the task you need to do is described), priority (how important is the task) and creation date (the date that the task was added to the to-do list). The derived field is the deadline field, which takes the creation date and the priority to calculate when the task should be finished by - 3 days in the future for high priority, 7 days for medium priority, and 14 days for low priority. When the button is clicked, the data is added to a list of "todo" data and the server updates the section to add the todo to the table.  

The CSS positioning technique I used was the grid technique. I decided on this instead of the flex box because the website was simple enough that a flexbox was not needed. The execution of this technique was done by creating a container for the form section and the results section and making them both items of the grid. Also, the Google font "epunda-slab" was used for all text on the screen.

## Technical Achievements
- **Tech Achievement 1**: Using a combination of the HTML tag <section> and the grid made with CSS, I was able to use JavaScript to take in data and display that data at the same time without having to refresh the page, as well as display both the input fields and the output fields on the same page.

I did not attempt to make a way to "modify" the data. 

### Design/Evaluation Achievements
- **Design Achievement 1**: I did not do an interview with another student, as this requirement was gotten rid of. 
