1. Print the first name, last name, and patronus of all characters who have a known patronus.

    SELECT fname, lname, patronus


    FROM characters


    WHERE NOT patronus = 'Unknown' AND patronus IS NOT NULL;T;

2. Print the last names of characters whose last name ends with the letter 'e'.

    SELECT * FROM hogwarts.characters


    WHERE lname LIKE '%e';

3. Calculate the total age of all characters and print it to the screen.

SELECT SUM(age) FROM hogwarts.characters;



4. Print the first name, last name, and age of the characters in descending order of their age.

    SELECT fname, lname, age FROM hogwarts.characters


    ORDER BY age DESC;

5. Print the names and ages of characters whose age is between 50 and 100 years..

    SELECT fname, age FROM hogwarts.characters


    WHERE age BETWEEN 50 and 100

6. Print the ages of all characters, ensuring that there are no duplicates..

    SELECT DISTINCT age


    FROM characterse;

7. Print all information about characters whose faculty is Gryffindor and whose age is over 30.

    SELECT * FROM hogwarts.characters


    WHERE faculty = 'Gryffindor' and age > 30;

8. Print the names of the first three faculties from the table, ensuring that there are no duplicates.

    SELECT faculty


    FROM hogwarts.characters


    GROUP BY faculty


    LIMIT 3;

9. Print the names of characters whose name starts with 'N' and has 5 letters, or whose name starts with “L”.

	SELECT fname

FROM characters

WHERE (fname LIKE 'N____' OR fname LIKE 'L%');



10. Calculate the average age of all characters

    SELECT AVG(age) FROM hogwarts.characters;

11. Delete the character with ID = 11.

    DELETE FROM hogwarts.characters


    WHERE ID = 11;

12. Print the last names of all characters that contain the letter 'a'

    SELECT lname FROM hogwarts.characters


    WHERE lname LIKE '%a%';

1. Use an alias to temporarily rename the column 'fname' to 'Half-Blood Prince' for the actual Half-Blood Prince

    SELECT fname AS "Half-Blood Prince"


    FROM hogwarts.characters


    WHERE fname = 'Severus' AND lname = 'Snape'

2. Print the IDs and names of all known patronuses in alphabetical order.

    SELECT char_id, patronus


    FROM characters


    WHERE NOT patronus = 'Unknown' AND patronus IS NOT NULL


    ORDER BY patronus ASC;;

3. Use the IN operator to print the first and last names of characters whose last name is Crabbe, Granger, or Diggory.

    SELECT fname, lname FROM hogwarts.characters


    WHERE lname IN ('Crabbe', 'Granger', 'Diggory');

4. Print the minimum age of the characters.

    SELECT MIN(age) FROM hogwarts.characters;

5. Use the UNION operator to print names from the characters table and book titles from the library table.

	SELECT fname FROM hogwarts.characters

UNION

SELECT book_name FROM hogwarts.library;

18. Use the HAVING operator to calculate the number of characters per faculty, keeping only those faculties where the number of students is greater than 1. \
 


    SELECT faculty, COUNT(*) FROM hogwarts.characters


    GROUP BY faculty


    HAVING COUNT(*) > 1;
