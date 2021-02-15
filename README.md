<h2>Amazing Prime</h2>
<p>Amazing Prime hosted a hackaton that required data from Wikipedia and Kaggle be combined and saved into a SQL database.  This SQL database provided the hackaton participants with a clean dataset.</p>
<h2>Summary</h2>
<p>The exctract, transform and loan process was followed to create a clean database.  Recognizing the time that this process takes Amazing Prime decided to create an automated pipline that takes new data, performs the appropriate transformations, and loads the data into existing databases.  In order to automate this process the code used to clean both the Wikipedia and Kaggle data were placed inside a function.  This function can then be called to clean imported files.  Using the function elininates the need to write code each time new data is received.</p>

