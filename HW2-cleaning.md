Arun Thakur, CS625-HW2 
# Homework 2: Data Cleaning

**Due:** Wednesday, September 20, 2023 by 11:59pm  

The goal of this week's assignment is to gain experience using OpenRefine for data cleaning.  

Downloaded and installed [OpenRefine](https://openrefine.org) version 3.7.4 and worked through the OpenRefine tutorial from Week 2 of CS 625.

## Assignment

Here is a report that describes how I carried out the tasks in Part 1 and how I arrived at the answers to the questions in Part 2.

### Report



### Part 1. Data Cleaning

Created a new project in OpenRefine and loaded the PetNames.tsv dataset available from <https://github.com/jgolbeck/petnames> (read the README.txt in that repo for more information on the dataset).  Missed out copying the URL directly into OpenRefine to load the data but downloaded it and uploaed it

Used OpenRefine to clean the dataset of pet names using Facet, sort extensively to answer the questions in Part 2.  Looked at the questions before starting cleaning to know what fields to pay attention to. Missed out taking notes to keep track of all operations I performed. Used OpenRefine facets and GREL transforms to clean the data and did some manual editing.

There are a couple entries where multiple pets are in the same entry, took a decision on how to handle these cases based on the data in other fields - PetName, PetBreed to chooese the best option.



Steps taken to clean the data: 
Clustering of all types using Text Facets and Number Facets.
Changing Age field to Number
Using regular expression in GREL to clean 5ish to 5 etc


Watched the tutorials and read documentation, including documentation on the [GREL regex language](https://openrefine.org/docs/manual/grel).


After cleaning the file:

* Exported the file as a new CSV and saved it in my repo as `HW2-petnames.csv`.
* Extracted JSON scripts containing all of the operations performed on the file and saved it in your repo as `HW2-petnames.json`. Used Export option > Templating to download the json file
  
* Included links to these files in your report.
 HW2-PetNames-txt-json.txt
 HW2-petnames-csv.csv

### Part 2. Analyze Cleaned Data

Use the cleaned data to answer the following questions in your report (and explain how you arrived at the answers):

1. How many types (kinds) of pets are there? 45
 
2. How many cats? 496
3. How many breeds of cats? 82
4. What's the most popular cat breed? How many cats are in that breed? Domestic Shorthair , Count 69
5. What's the age range of the cats? 0.25 to 25 years
6. What's the age range of the rabbits? (*Don't forget to look for bunny, too.*) 1.75 to 13 year
7. What is the oldest pet? Give the pet's name, kind, and age. Dog, Name: Dino, Breed: Keeshound, Age: 30 years
8. What are the top 5 most popular dog breeds? List the breed and number. Golden Retriever 156, Mutt 35, Labrador Retriever 
   24, Beagle 19, Border Collie 17
9. What's the most popular everyday name for a dog? Charlie
10. What's the most popular full name any pet? Sophie

*I do not expect everyone to have the exact same answers. Some of these will depend upon decisions you make while cleaning the data. Note in your report any cleaning decisions you made that could impact your answers.*
Combined similar sounding names, combined Rabbits and Bunnies

## Submission

Worked in the private GitHub repo created for me in the [odu-cs625-datavis organization](https://github.com/odu-cs625-datavis/).  Committed to repo, including files to GitHub. 

For this assignment, GitHub repository includes the following files:

* `HW2-report.md` - your report
* `HW2-petnames.csv` - cleaned CSV
* `HW2-petnames.json` - operations used to clean the data in JSON format
  

Submitted the URL of your report (*not the URL of your repo*) in Canvas under HW2. Arun Thakur, CS625-HW2 
# Homework 2: Data Cleaning

**Due:** Wednesday, September 20, 2023 by 11:59pm  

The goal of this week's assignment is to gain experience using OpenRefine for data cleaning.  

Downloaded and installed [OpenRefine](https://openrefine.org) version 3.7.4 and worked through the OpenRefine tutorial from Week 2 of CS 625.

## Assignment

Here is a report that describes how I carried out the tasks in Part 1 and how I arrived at the answers to the questions in Part 2.

### Report



### Part 1. Data Cleaning

Created a new project in OpenRefine and loaded the PetNames.tsv dataset available from <https://github.com/jgolbeck/petnames> (read the README.txt in that repo for more information on the dataset).  Missed out copying the URL directly into OpenRefine to load the data but downloaded it and uploaed it

Used OpenRefine to clean the dataset of pet names using Facet, sort extensively to answer the questions in Part 2.  Looked at the questions before starting cleaning to know what fields to pay attention to. Missed out taking notes to keep track of all operations I performed. Used OpenRefine facets and GREL transforms to clean the data and did some manual editing.

There are a couple entries where multiple pets are in the same entry, took a decision on how to handle these cases based on the data in other fields - PetName, PetBreed to chooese the best option.



Steps taken to clean the data: 
Clustering of all types using Text Facets and Number Facets.
Changing Age field to Number
Using regular expression in GREL to clean 5ish to 5 etc


Watched the tutorials and read documentation, including documentation on the [GREL regex language](https://openrefine.org/docs/manual/grel).


After cleaning the file:

* Exported the file as a new CSV and saved it in my repo as `HW2-petnames.csv`.
* Extracted JSON scripts containing all of the operations performed on the file and saved it in your repo as `HW2-petnames.json`. Used Export option > Templating to download the json file
  
* Included links to these files in your report.
 HW2-PetNames-txt-json.txt
 HW2-petnames-csv.csv

### Part 2. Analyze Cleaned Data

Use the cleaned data to answer the following questions in your report (and explain how you arrived at the answers):

1. How many types (kinds) of pets are there? 45
 
2. How many cats? 496
3. How many breeds of cats? 82
4. What's the most popular cat breed? How many cats are in that breed? Domestic Shorthair , Count 69
5. What's the age range of the cats? 0.25 to 25 years
6. What's the age range of the rabbits? (*Don't forget to look for bunny, too.*) 1.75 to 13 year
7. What is the oldest pet? Give the pet's name, kind, and age. Dog, Name: Dino, Breed: Keeshound, Age: 30 years
8. What are the top 5 most popular dog breeds? List the breed and number. Golden Retriever 156, Mutt 35, Labrador Retriever 
   24, Beagle 19, Border Collie 17
9. What's the most popular everyday name for a dog? Charlie
10. What's the most popular full name any pet? Sophie

*I do not expect everyone to have the exact same answers. Some of these will depend upon decisions you make while cleaning the data. Note in your report any cleaning decisions you made that could impact your answers.*
Combined similar sounding names, combined Rabbits and Bunnies

## Submission

You should be working in the private GitHub repo that I created for you in the [odu-cs625-datavis organization](https://github.com/odu-cs625-datavis/).  If you are working locally, make sure that you have committed and pushed your local repo, including any images you reference, to GitHub. 

For this assignment, your GitHub repository should include the following files:

* `HW2-report.md` - your report
* `HW2-petnames.csv` - cleaned CSV
* `HW2-petnames.json` - operations used to clean the data in JSON format
*  any images that you reference in your report

Submit the URL of your report (*not the URL of your repo*) in Canvas under HW2. 

References: links to examples used in completing this assignment.
https://openrefine.org/docs/manual/grelfunctions
https://chat.openai.com/c/4f18ce9d-238f-4593-84e6-096d3ae48a90



References: links to examples used in completing this assignment.
https://openrefine.org/docs/manual/grelfunctions
https://chat.openai.com/c/4f18ce9d-238f-4593-84e6-096d3ae48a90


