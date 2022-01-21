# birthday-tracker
A very simplistic web application that allows users to keep track of peoples' birthdays. Technologies employed include HTML, CSS, SQL, and Python. 

![Index Page Screenshot](/readme_imgs/index.png)

### How to run the application
1. Download this repository as a zip file and extract the contents.
2. Open a command prompt terminal and change directory to the folder extracted in the step above. 
3. Type the following command:

    > flask run
4. Copy the link generated and type it into a web browser. The link is displayed at the last line that looks like the following:

    > INFO:  * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)

### Application Strcuture & explanation of files/folders
- **/static:** static data such as CSS files are stored in this folder as per Flask standards. 
- **/templates:** HTML files of the application are stored in this folder as per Flask standards.
- **app.py:** a python file defining the backend logic of the application.
- **birthdays.db:** a SQLite database file consisting of one table that stores peoples' names, month of birth, and day of birth.
