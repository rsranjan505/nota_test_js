# nota_test_js
- Please place your solutions in separated folders:
  - task1 - for Task 1
  - task2 - for Task 2 
- Please comment the code

# **Task 1**
Please feel free to use JQuery framework   to complete this task.

Create 3 buttons with names 1, 2, 3, located one above the other.

![image](https://github.com/mskozhanova/nota_test_js/assets/17182091/98d45fab-911c-4b4d-ba73-9e87d24af583)

After the click on any button this button should change places with it's upper neighbor if any exists. If no upper neighbor exists the button should change places with it's below neighbor.
Your solution should be scalable for adding more buttons (4, 5, etc)

Please comment the code.

# **Task 2**

You can use jquery or other JS framework

- Receive some data from the backend (can mock the data) and display the received data in a table. Data fields are:
ID - integer, unique
name - text, up to 256 characters
datetime - Date time of adding the record

- Add new entry button; after the click the field for name and Send button appears; after click to Send button a request goes to backend; on success the new ID returns and a new row with data appears in the table

- Add delete button opposite each row of the table;  after the click the record is deleted by a request on the backend; on success, it is deleted on the frontend

- Edit button next to each row of the table
By clicking on it, name input in the row  becomes editable and in place of the edit button, a save button appears
By clicking on save, a request is sent to the backend; if successful, the inputs become ready again and the button changes to “edit”.

- If error appears during request please show it (not in alert)

- You can mock all requests

Please comment the code.
