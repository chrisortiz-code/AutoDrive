# AutoDrive Website

The **AutoDrive Website** is a web platform for managing car listings, user authentication, and personalized wishlists. Built using PHP, MySQL, and JavaScript, it supports administrative controls and user-specific features through secure interactions with a relational database.

---

## Features

### 1. **User Authentication**
- **Login Encryption and Verification**:
  - Secure login system with encrypted passwords.
  - Authentication queries the `users` database.

### 2. **Admin Hub**
- **Car Information Management**:
  - Admins can update car details such as price, description, and tags.
  - Changes are reflected in the `products` database.

- **User Management**:
  - Ban/unban users.
  - Grant or revoke admin privileges.

### 3. **Wishlist Management**
- Users can:
  - Add/remove cars to/from their wishlist from individual product pages or the wishlist page.
  - Wishlist data is stored in the `cart` column of the `users` database in the format: `carId-carId-carId`.

---

## Technology Stack

- **Backend**: PHP
- **Database**: MySQL (Relational Database)
- **Frontend**: JavaScript, HTML, CSS
- **Form Handling**: PHP POST Requests
- **Security**: Encrypted Login and Verification

---

The AutoDrive Website is available at: 

[http://cosc.brocku.ca/~tl22ba/A4/](http://cosc.brocku.ca/~tl22ba/A4/)

---

