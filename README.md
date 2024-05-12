# automate
python to automate file downloads from canvas

The idea of this project is to create a system to automatically categorize files downloaded from canvas for school
This project should do the following:

- locate and extract course data from the syllabus
- confirm data with the user
- run automatically to put the user downloaded file in the appropriate course folder
- categorize courses with subfields such as exams, quizzes, homework, slides
- subcategorize downloads by time - i.e. what exam does each download pertain to chronologically?

Solution?

- Ideally parse through the PDF and use NLP to get the data we want, then confirm with the user and allow them to edit
  (only tradeoff is if we confirm with the user at the end and it's wrong the whole thing is redundant, so why not just do manual input for now? and still populate folders)
  
-Then search through the downloaded course files every time one is downloaded
  1. first for course context? What class is it for? Compare keywords from user input with data on file
  2. then populate the folders
