# LAB - Class 01

## Project: Snakes Café

### Author: Kassie Bradshaw

---

### Feature Tasks & Requirements

* [ ] When run, the program should print an intro message and the menu for the restaurant
* [ ] The restaurant's menu should include appetizers, entrees, desserts, and beverages
* [ ] The program should prompt the user for an order
* [ ] When a user enters an item, the program should print an acknowledgement of their input
* [ ] The program should tell the user how to exit
* [ ] The program's content should match the included sample exactly
  * [ ] Actually, there's one tiny spot that should be different - see if you can spot it.
  * [ ] The `>` character represents user input line and should be printed out with a trailing space.
  
### Stretch Goals

* [ ] Print out a summary of a complete order.
* [ ] Only allow ordering items on the menu.
* [ ] Allow ordering items not on menu but give custom reply.

---

### Samples

```python
$ python snakes_cafe.py
**************************************
**    Welcome to the Snakes Cafe!   **
**    Please see our menu below.    **
**
** To quit at any time, type "quit" **
**************************************

Appetizers
----------
Wings
Cookies
Spring Rolls

Entrees
-------
Salmon
Steak
Meat Tornado
A Literal Garden

Desserts
--------
Ice Cream
Cake
Pie

Drinks
------
Coffee
Tea
Unicorn Tears

***********************************
** What would you like to order? **
***********************************
>
```

#### Entering an order

```python
***********************************
** What would you like to order? **
***********************************
> Wings

** 1 order of Wings have been added to your meal **

> Wings

** 2 orders of Wings have been added to your meal **
```

#### Exiting

```python
> quit
```

---

### Links and Resources

* back-end server url (when applicable)
* front-end application (when applicable)

---

### Setup

* `.env` requirements (where applicable)
  * PORT - Port Number
  * DATABASE_URL - URL to the running Postgres instance/db

---

### How to initialize/run your application (where applicable)

e.g. `python main.py`

---

### How to use your library (where applicable)

---

### Tests

* How do you run tests?
* Any tests of note?
* Describe any tests that you did not complete, skipped, etc
