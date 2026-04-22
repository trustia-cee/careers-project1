# Technical Test - Trustia

## Exercise 1

Create a Python program that prints text blocks in the console, framed like in the provided example.
<img width="1045" height="276" alt="image" src="https://github.com/user-attachments/assets/79044160-18e5-4b53-9783-ec3b2b222733" />

### Constraints

- The maximum width of a block is **100 characters** and must be easy to modify.
- All text must be displayed in **lowercase**.
- Blocks may contain **one or more lines**.
- Borders must use `-` for horizontal lines and `|` for vertical sides.

### Data Organization

- All sentences must be stored in a **dictionary**.
- Some sentences may remain in the dictionary **without being displayed**.
- The display order must be **easy to modify**.

### Blocks to Produce

#### Block 1

- Clean code makes maintenance easier

#### Block 2

- Testing often avoids many errors
- This sentence must not be displayed

#### Block 3

- This sentence must not be displayed
- Good code should remain simple and clear
- Simplicity improves code quality
- Refactoring improves understanding

### Important Rule

The following sentences **must not appear in the console**, even if they are present in the dictionary:

- `"This sentence must not be displayed"` (block 2)
- `"Good code should remain simple and clear"` (block 3)

### Goal

The code must make it easy to:

- modify the text
- change the order of the blocks
- add or remove lines
- keep some sentences in the dictionary without displaying them

---

## Exercise 2

Create a Django web application to manage products and generate invoices.

### Constraints

- You must use the **Django** framework
- Products must contain:
  - id
  - name
  - price
  - expiration date
- The application must allow:
  - create
  - update
  - delete
  - display products
- Lists must use a **pagination** system

### Data Organization

- Products are stored in a **database**
- An invoice can contain **multiple products**
- Each product in an invoice can have a **quantity**

### Features to Deliver

#### Product Management

- Create a product
- Edit a product
- Delete a product
- Display the product list

#### Invoicing

- Create an invoice
- Select products for the invoice
- Set the quantity for each product

#### Invoice Detail Page

- List of products in the invoice
- Total number of products
- Total amount to pay

### Goal

The application must make it easy to:

- add or modify products
- create invoices with multiple products
- view invoice details
- navigate through lists with pagination

---

## Exercise 3
Please send a link to your portfolio, only including your personal projects, to **jacques.zhuang@trustia.ai**.

---

## Stack

- Django / Python
- HTML / CSS / JavaScript
- Django database system (SQLite or another database)

---

## Use of Tools

- The use of AI tools is allowed
- However, it is **not recommended to use AI for Exercise 1**, in order to evaluate your logic

---

## Submission Format

The work must be submitted as a **public Git repository**.

### The repository must contain:

#### Exercise 1

- A single Python file containing the requested program

#### Exercise 2

- A complete Django project, including:
  - product management
  - invoicing system
  - pagination

---

## Submission

Send the repository link by email to:

**jacques.zhuang@trustia.ai**
