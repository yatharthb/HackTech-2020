# Patient Matching Challenge

Here is the Proof of Concept Patient Matching algorithm by Office Ally.  In our limited testing, it has shown to be at least 90% accurate.

Utilizing this and the Test Patient Data provided, perform the following:

1. Store the CSV data into a database.  It can be any database that you feel comfortable working with.  This data was extracted from SQL Server.
2. Once the database is created and patient data imported, you can use the SQL POC provided to run some tests to verify the accuracy of the current algorithm.
3. Now, create an application based version of the SQL proof of concept.  Use Python or C# (ASP.Net) to complete this.  
    - Your application basically does what the SQL POC does.
4. Once you have created an application that mirrors the SQL POC, you can hook up the database to your application, and verify your accuracy is the same as the SQL POC.
5. Finally, what else can you do to improve the accuracy of the Patient Matching in your application?  Think of other perspectives you can utilize the data to perform comparisons.
    - The proof of concept utilizes hash tokens and Soundex tokens.  Are there any other ways to improve matching accuracy?
