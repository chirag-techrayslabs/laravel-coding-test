# Online Bookstore Coding Test

## Task Overview

You are required to create a simple online bookstore application using Laravel. The application should include the following features:

- **Front-End:**
  - A page to list all books.

- **Admin Panel:**
  - Functionality to create and update book records.

## Requirements

### 1. Book Listing

Create a page that displays a list of all books. Each book should show the following information:

- Title
- Author
- Description
- Price

### 2. Admin Book Management

Implement the following features for book management:

- **Create Book:**
  - Admin should be able to create a new book.
  - Validate the following fields:
    - `title`: required, string, max: 255
    - `author`: required, string, max: 255
    - `description`: optional, string
    - `price`: required, numeric

- **Update Book:**
  - Admin should be able to update existing book details.
  - Validate the same fields as in book creation.

### 3. Validations

Ensure the following validations for book creation and update:

- `title`: required, string, max: 255
- `author`: required, string, max: 255
- `description`: optional, string
- `price`: required, numeric

## Submission

- Create a new Laravel project.
- Implement the required features.
- Ensure the project is functional and meets all requirements.
- Upload the project to a public GitHub repository.
- Share the repository link.

## Evaluation Criteria

- Code quality and organization.
- Correctness and completeness of features.
- Proper use of Laravel conventions and best practices.
- Handling of form validations.
- Clear and user-friendly UI for book listing and admin management.

Good luck!
