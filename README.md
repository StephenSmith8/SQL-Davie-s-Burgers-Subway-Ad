# SQL-Davies-Burgers-Subway-Ad

Project Overview

The project was based on a fictional restaurant called Davie's Burgers where the obect is to help them dig into their 'orders' table to see if their is anything interesting in their for funny tag line.

The project included the requirement to write the following queries:

1. Start by getting a feel for the orders table. What are the column names?
2. How recent is this data? Use DISTINCT to find out all the unique order_date values in this table.
3. The special_instructions column stores the data where Davie’s Burgers customers leave a note for the kitchen or the delivery. Instead of selecting all the columns using *, write a query that selects only the special_instructions column. Limit the result to 20 rows.
4. There seem to be a lot of empty values in that column. That is because customers sometimes leave the notes section blank. Can you edit the query so that we are only returning the special instructions that are not empty?
5. Let’s go even further and sort the instructions in alphabetical order (A-Z).
6. Awesome! Now we have a good idea of the list. Let’s search for special instructions that have the word ‘sauce’. Are there any funny or interesting ones?
7. Let’s search for special instructions that have the word ‘door’. Any funny or interesting ones?
8. Let’s search for special instructions that have the word ‘box’. Any funny or interesting ones?
9. Wow, some of these are marketing gold! But what are their order numbers? Instead of just returning the special instructions, also return their order ids.

- For more readability:
  - Rename id as ‘#’
  - Rename special_instructions as ‘Notes’


