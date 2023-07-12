# Airline-System-DWH-Modeling
### 📌 Project Description
A major airline company decided to hire you to assist the executive management to analyze
their current business processes and expand the company by discovering new opportunities.
Executives decided that the first deliverable should focus on the flight activity to ensure good
ongoing business process.
The marketing department wants to analyze what flights the company’s frequent flyers take,
what fare basis they pay, how often they upgrade, how they earn and redeem their frequent
flyer miles, whether they respond to special fare promotions, how long their overnight stays
are, and what proportion of these frequent flyers have gold, platinum, aluminum, or titanium
status.
Your analysis shall also include the reservation process where finance team will be interested in
analyzing the company profit. Note that reservation processes can take place through multiple
channels.
Airline company also provides customer care interaction before, within and after your trip to
handle customer inquiries, complaints and keep their feedback for business enhancements.
Analysis should include interaction type and problem severity (if issue exists)
Apply dimensional modeling process to design the logical and physical design to support such
kind of analysis for decision support.

### 📌 project prequirments:
> 1. State the dimensional modeling process for each business process
> 2. Using any diagramming tool you like, construct a logical data model for this case
study. Output should be an image or PDF. State why did you choose this
particular data model design? What does the data represent? (Details about each
model component is necessary).
> 3. Translate the logical data model to a physical data model which includes the
following: tables, columns (name, data type), primary indexes, and foreign indexes
and state why these types of indexes are used for each column. Output should be a
Word or Excel file.
> 4. Create the table in oracle DBMS and populate sample data to be used in your
queries.
> 5. Construct a sample of SQL queries (5 – 8 queries) using your physical model design
which can be used to answer possible questions by the .decision maker as
described in the case-study above. List the business question with each query.
Output should be a Word file
> 6. A report of maximum 2 pages is required to elaborate different types of indexes
used in Data warehousing and their usage

### 📌 Project phases:
1. Extracted and investigated each business process's objectives, terminologies, and activities from the assigned case study PDF.

2. Created a draft Word document with our findings regarding each department's needed queries that we need to answer with our model.
  
3. Developed a prototype ERD in Excel with about 5 records for each table to visualize the flow of the transactional DB. Ensure the process is logical without any gaps, starting from a customer purchasing a ticket, recording the purchase, and identifying the tables that the transaction could affect.

5. At this phase we were able to  plan our DWH that in real life would extract the needed data from the transactional database.
   
6. Created a logical data model for each department ( Marketing team, finance team, customer satisfaction interested parties).

7. Created a physical data model using MySQL.

8. We populated our physical data model with fictitious records using the logic based on the ERD system we developed initially. This allowed us to test our queries and provide answers to required questions.

### 📌 Exploring the project:
> 1. you can find our final 3 logical data models ( Finance, activity, Feedback),  each with an attached Word document explaining their contents.

> 2. The next step is to view the physical data model.

> 3. Finally, you can Check the "queries.xlsx" file to see how each department's needed inquiries were answered using our DWHs.

> 4. Also you can view the Drafted document and ERD system, where we start collecting ideas and inserting our findings.

