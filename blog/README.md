# Django Blog with Authentication and Authorization

This is a simple Django blog application with user authentication and authorization features. Users can register, log in, create blog posts, and log out. Different user roles (such as admin, author, and reader) are supported with varying levels of permissions.

## Installation

1. **Clone the Repository**: 


2. **Install Django**: 

3. **Navigate to the Project Directory**: 

4. **Apply Migrations**: 

5. **Create a Superuser** (for admin access):

6. **Run the Development Server**: 

7. **Access the Admin Interface**:
- Open a web browser and go to `http://127.0.0.1:8000/admin`
- Log in using the superuser credentials created in step 5.

## Usage

1. **Register a New User**:
- Visit `http://127.0.0.1:8000/register` to create a new user account.

2. **Log In**:
- Visit `http://127.0.0.1:8000/login` to log in with your credentials.

3. **Create a Blog Post**:
- Once logged in, visit `http://127.0.0.1:8000/create/` to create a new blog post.

4. **View Blog Posts**:
- The home page (`http://127.0.0.1:8000/`) displays all blog posts.

5. **Log Out**:
- Click on the "Logout" link to log out from your account.

## Features

- User Authentication: Users can register, log in, and log out.
- User Authorization: Different user roles (admin, author, reader) with varying levels of permissions.
- Blog Post Creation: Authenticated users can create new blog posts.
- Access Control: Certain actions (e.g., creating blog posts) are restricted to authenticated users.
- Admin Interface: Superusers can manage users, blog posts, and other site settings through the Django admin interface.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/improvement`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/improvement`).
6. Create a new Pull Request.


