# MyPostPilot-Django-Post-Management-System

MyPostPilot is a Django-powered web application that allows users to create, manage, and interact with categorized blog posts. Designed as a beginner-friendly, full-stack project, it includes user authentication, categorized content, image uploads, tag-based search, and a personalized profile dashboard.

✅ Key Modules & Features
Authentication System:
Users can register, log in, and log out securely using Django’s built-in auth system.

Category-Based Organization:
Posts are organized under predefined categories such as:
Education
Health & Fitness
Technology
Lifestyle
Personal Development

Post Management:
Authenticated users can:
  Create posts with title, description, image, and tags
  Edit or delete their own posts
  View their posts from the profile section
Comment System:
  Users can add, edit, and delete comments on posts. Comments are linked to both the post and the user.
Search Functionality:
  Users can search posts based on tags using a keyword-based search box.
User Profile Page:
  Displays all posts and comments made by the logged-in user, with options to edit/delete each.
Email Integration:
  On registration, users receive a welcome HTML email using Django’s email backend.

🧱 Technical Details
Framework: Django 5.x
Database: SQLite (easily swappable with MySQL/PostgreSQL)
Templates: 13 separate responsive HTML pages
Image Uploads: Managed using MEDIA_ROOT and MEDIA_URL
Styling: CSS-based custom design (can be extended using Tailwind or Bootstrap)
Security: Login required for posting, commenting, editing, and profile views

📦 Included HTML Templates
home.html, login.html, register.html, base.html, navbar.html
category_list.html, category_detail.html, create_post.html, all_posts.html
search_results.html, my_profile.html, my_post.html, my_comment.html, edit.html
emails.html (HTML email template)

📚 Learning Outcomes
This project is ideal for understanding:
Django Models, Views, and Templates (MVT)
User authentication and session management
File/image handling in Django
Basic email integration
Dynamic content filtering and querying
CRUD operations in a multi-user environment
