# Sydney-Uni-Junior-Mathematicians
Data science exploration into characteristics of the best and worst junior mathematicians at Sydney University in 2018. The final report is created through knitting the code base in RStudio.

## Data dictionary
The data set contains 10845 anonymised student grades from the top 15 most popular Mathematics units in 2018 at the University of Sydney. Each row denotes a student's enrolment in a particular unit of study.

**Student Enrolment Key:** A unique identifier for each row in the data set.

**Unit of Study Identifier:** An anonymous identifier for the unit of study.

**Semester:** The semester that the unit of study was run in. Unit of study occurences outside Semester 1 and 2 (for example, intensive or Summer/Winter school units) have been excluded from the data set.

**Dom/Int:** Whether the student is domestic or international.

**Gender:** The gender of the student. "M" denotes male, "F" denotes female and those who identify as neither.

**Mode of Study:** Whether the student is full time or part time. Full time is defined as taking more than 18 credit points in the semester in which the student too the unit of study.

**Age:** The age of the student at the first day of semester for the unit of study. There are 4 categories:
- 18 and under
- 19-21
- 22-25
- Over 25

**Unit of Study Mark:** The final mark achieved by the student. Student enrolments with non-standard grades (for example, discontinuations, withdrawals, absent fails and the like) have been removed from the data set to preserve anonymity.

**Canvas access:** Fifteen columns are included, one for each week of the semester includign the mid-semester break and STUVAC, denoting whether or not the student accessed the Canvas site for that unit of study at least one during the given week. Student who did not access Canvas over the whole semeseter have been excluded from the data set.
