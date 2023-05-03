Download Link: https://assignmentchef.com/product/solved-cs384-tutorial-4-academic-subject-record-with-excel-output
<br>
PS: This is an old list of courses. You may find your roll number here, but ignore the details. Its just for your practise.

<strong>Task 1</strong>:

You are given a “regtable old.csv” file containing the subjects taken by IITP students. You need to make files for individual roll numbers with their subject information.

Template of “regtable old.csv” is as follows:

<strong>rollno</strong>: Roll number of the student <strong>register sem</strong>: Semester for which registered. <strong>schedule sem</strong>: Semester for which registered . <strong>subno </strong>: Course Code. <strong>grade1</strong>: Ignore. <strong>date ofentry1</strong>: Ignore.

<strong>grade2</strong>:Ignore . <strong>date ofentry2</strong>: Ignore.

<strong>sub type</strong>: Core/Elective.

If a roll number has taken <em>k </em>subjects, there would be <em>k </em>rows against the roll number in the input file “regtable old.csv”. Your task to read the “regtable old.csv” file using the csv library and make <em>k </em><strong>xlsx </strong>files corresponding to <em>k </em>roll numbers. A sample output for Task 1 is shown in 1901EE01.xlsx file.

Check the sample output folder 1901EE01.xlsx rollno,register sem,subno,sub type

1901EE01,5,CS384,Open Elective

1901EE01,5,EE330,CORE

1

1901EE01,5,EE331,CORE

1901EE01,5,EE350,CORE

1901EE01,5,EE370,CORE

1901EE01,5,EE372,CORE

1901EE01,5,EE381,CORE

All of the outputs for Task 1 should go into the folder “output individual roll” <strong>Task 2</strong>:

Now you need to make a file for every individual subject listed in the “regtable old.csv”. Read the <strong>subno </strong>column and for each individual subject that have taken those subject. Check the file sample output CS384.xlsx file and make for all unique subjects.

All the outputs relating to Task 2 should go into “output by subject” folder.

I placed the sample output folder just for ease of viewing the output. Your outputs should go to folders as described in Task 1 and Task 2.