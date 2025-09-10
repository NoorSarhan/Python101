Exercises
The exercises will be split to 3 main parts:

Easy
Medium
Hard
Easy
Exercise 1
Write a python program that:

Asks the user about their name
Save it in a variable called "name"
Asks the user about their age
Save it in a variable called "age"
Print a string stating "The user -name- is -age- years old"
Exercise 2
Ask the user for a number. Depending on whether the number is even or odd, print out an appropriate message to the user. Hint: how does an even / odd number react differently when divided by 2?

Extras:

If the number is a multiple of 4, print out a different message. Ask the user for two numbers: one number to check (call it num) and one number to divide by (check). If check divides evenly into num, tell that to the user. If not, print a different appropriate message.

Exercise 3
Write a program that takes a list of numbers (for example, a = [5, 10, 15, 20, 25]) and makes a new list of only the first and last elements of the given list. For practice, write this code inside a function.

Exercise 4
Write a function that takes an ordered list of numbers (a list where the elements are in order from smallest to largest) and another number. The function decides whether or not the given number is inside the list and returns (then prints) an appropriate boolean.

-> Solution: https://www.practicepython.org/exercise/2014/11/11/20-element-search.html

Medium
Exercise 1
Write a Python program to find three numbers from an array such that the sum of three numbers equal to zero. Input : [-1,0,1,2,-1,-4] Output : [[-1, -1, 2], [-1, 0, 1]] Note : Find the unique triplets in the array.

Exrecise 2
Build a simple text analyzer. Problem: Write a function count_words(text) that:

Accepts a paragraph of text
Returns a dictionary where keys are words and values are how many times they appeared (case-insensitive)
Example input: | text = "AI is the future. The future is now."

Expected Output: {'ai': 1, 'is': 2, 'the': 2, 'future': 2, 'now.': 1}

Exercise 3
| Practice object-oriented programming, attributes, and methods. Build a basic system to manage books in a library.

🧠 Requirements:

Create a Book class with:
Attributes: title, author, year, is_checked_out (default = False)
Method: checkout() → sets is_checked_out = True
Method: return_book() → sets is_checked_out = False
Method: str() → returns a string like: "1984 by George Orwell (Checked out: False)"
Create a Library class with:
Attribute: a list called collection to store books
Method: add_book(book) → adds to collection
Method: list_books() → prints all book titles and status
Method: find_book(title) → returns a matching book (case-insensitive)
Example Usage

b1 = Book("1984", "George Orwell", 1949)
b2 = Book("The Alchemist", "Paulo Coelho", 1988)

lib = Library()
lib.add_book(b1)
lib.add_book(b2)

lib.list_books()

b1.checkout()
lib.list_books()

found = lib.find_book("1984")
print(found)
🚀 Bonus Challenge:

Add a method available_books() in the Library class to list only books that are not checked out.
