Arun Thakur, CS625-HW2 
# Homework 2: Data Cleaning

**Due:** Wednesday, September 20, 2023 by 11:59pm  

The goal of this week's assignment is to gain experience using OpenRefine for data cleaning.  

Downloaded and installed [OpenRefine](https://openrefine.org) version 3.7.4 and worked through the OpenRefine tutorial from Week 2 of CS 625.

## Assignment

Write a report that describes how you carried out the tasks in Part 1 and how you arrived at the answers to the questions in Part 2.

### Report



### Part 1. Data Cleaning

Create a new project in OpenRefine and load the PetNames.tsv dataset available from <https://github.com/jgolbeck/petnames> (read the README.txt in that repo for more information on the dataset).  If you view the raw version of the data file in GitHub, you can copy that URL directly into OpenRefine to load the data without downloading it separately.

Use OpenRefine to clean the dataset of pet names so that you can answer the questions in Part 2.  Look at the questions before you start cleaning so that you know what fields to pay attention to. Take notes and keep track of all operations you perform. As much as you can, use OpenRefine facets and GREL transforms to clean the data rather than manual editing (though, some cleaning will need to be done manually).

There are a couple entries where multiple pets are in the same entry. Make a decision on how to handle these cases and document it in your report.



In your report, explain the steps you took to clean the data. Include screenshots, GREL statements, etc. as needed to clearly document what you did. If you did any manual cleaning, note that and explain why you did this manually. Include enough detail so that I am convinced that you understand how to use OpenRefine.

You will likely not have learned everything in class that you need to know to complete the assignment. I expect that you will watch the tutorials and read documentation, including documentation on the [GREL regex language](https://openrefine.org/docs/manual/grel).

When you are done cleaning the file:

* Export the file as a new CSV and save it in your repo as `HW2-petnames.csv`.
* Extract JSON scripts containing all of the operations you performed on the file and save it in your repo as `HW2-petnames.json`. (Select **Extract** at the top of the **Undo/Redo** tab. Then copy and paste the JSON script into a new file.)
* Include links to these files in your report.

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

Submit the URL of your report (*not the URL of your repo*) in Canvas under HW2. This should be something like  
https<nolink>://github.com/odu-cs625-datavis/fall23-asv-*username*/blob/main/HW2-report.md

References: links to examples used in completing this assignment.
https://openrefine.org/docs/manual/grelfunctions
https://chat.openai.com/c/4f18ce9d-238f-4593-84e6-096d3ae48a90


