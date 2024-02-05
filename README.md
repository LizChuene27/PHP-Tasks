## Task 1: Problem Solving

### Identified Errors:
- Syntax error
- Logical errors
- Missing parenthesis

### Corrections Made:
- The opening script for PHP is <?php instaed of </php and ends with ?>
- Replaced assignment with equality check. == is used to compare two values and will return true but with = left side is set to the expression of the right
- I removed ) as there were two and one missed an opening.

## Task 2: Class Refactor Task

### Changes Made:
- Refactored the `get_products` function into a `ProductManager` class
- I brought the products together by for of encapsulation and put them in a private class
- I added construct that takes in $products array using the word "construct"
- To retrieve productId from Product class, I used the "get" method
- Utilized dependency injection

## Task 3: Data Retrieval Task

### Integration with Google Sheets API:
- Created a class `GetDataFromSheet` to fetch products from Google Sheets
- Used file_get_contents and not any PHP library such as Composer
- Google Sheet was shared with everyone with link

  ### Challenges I faced with the task
  - I struggled with using composer as a library for my data retrieval task as it had a lot of dependecies however that didn't stop me from finding alternative solutions. I then used the 'GetDataFormSheet' to fetch products from Google sheets. My overall experience was very good, I thoroughly enjoyed problem solving and being opened to new things.
