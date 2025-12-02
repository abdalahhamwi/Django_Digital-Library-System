# Digital Library System
A demo project for a Digital Library System built with Django. It provides full management of books including adding, categorizing, selling, borrowing, and tracking profits, with a simple admin-like dashboard.

 Key Features :
Add New Books: Enter title, author, number of pages, price, and status.

Category Management: Create, edit, and delete categories (History, Art, Culture, Romance...).

Book Status:

Available ✅

Borrowed 📖

Sold 💰

Dashboard Statistics:

Total number of books.

Profits from sales.

Profits from borrowing.

CRUD Operations: Full support for Create, Read, Update, Delete.

Admin Panel: Manage books and categories easily through Django Admin.

 User Interface 
The system provides a clean and functional dashboard

Dashboard Overview:

Displays all books with details (title, author, category, pages, price, status).

Quick statistics for total books, borrowed, sold, and profits.

Book Management:

Edit book details (title, author, price, status, category).

Delete books permanently.

Add new books via structured forms with validation.

Category Management:

Create, update, and delete categories.

Filter books by category.

Status Indicators:

✅ Available

📖 Borrowed

💰 Sold

Responsive Design:

Built with Bootstrap for mobile-friendly layout.

Works smoothly on desktop, tablet, and mobile.

🏗️ Tech Stack
Language: Python 🐍

Framework: Django (Models, Views, Templates, Admin)

Database: SQLite (can be replaced with PostgreSQL or MySQL)

Frontend: HTML, CSS, Bootstrap

Admin Panel: Django Admin

Libraries:

Django ORM for database relations

Bootstrap for styling

🚀 How to Run
Make sure you have Python and Django installed.

Clone the repository:

bash
git clone https://github.com/abdalahhamwi/Django_Digital-Library-System.git
Navigate to the project folder and run the server:

bash
cd Django_Digital-Library-System
python manage.py runserver
Open your browser at:

bash
http://127.0.0.1:8000/
