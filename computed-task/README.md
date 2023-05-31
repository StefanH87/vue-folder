Task: Computed properties & Methods
In this task we use the Computed properties & Methods. Sources will be found in the src folder of this directory. We are a book store and like to show our customers a list with books with a 20% discount off all O'Reilly Media books.

Fulfill the following tasks:

Write all your js code in the scripts.js file
The table head gets rendered with a v-for based on the keys of the first element in the books array Object.keys(books[0]).
Use a computed property instead of wirting Object.keys(books[0]) in the template.
Ensure that the table head matches the expected entries (e.g. column isbn lists all isbns and not the title).
Use a computed property to only display Books from the publisher O'Reilly Media
All prices should be displayed with a discount of 20%
Use a method to calculate a new price for each book with the discount
Sample solution
https://codepen.io/may17-the-typescripter/pen/abVzwra?editors=0010
