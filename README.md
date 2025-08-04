# Project--Shikhar-shikverm

**Task 1
**Project Title: Library Management System (using SQL)

Project Overview:
This Library Management System is a SQL-based database solution designed to efficiently manage library operations including book inventory, member management, and borrowing transactions. The system provides comprehensive functionality for tracking books, managing member information, and monitoring borrowing activities.

Database Structure
Tables
Books

BOOK_ID (Primary Key)
TITLE
AUTHOR
GENRE
YEAR_PUBLISHED
AVAILABLE_COPIES
Members

MEMBER_ID (Primary Key)
NAME
EMAIL
PHONE_NO
ADDRESS
MEMBERSHIP_DATE
BorrowingRecords

BORROW_ID (Primary Key)
MEMBER_ID (Foreign Key)
BOOK_ID (Foreign Key)
BORROW_DATE
RETURN_DATE
Key Features
Basic Operations
Book inventory management
Member registration and management
Borrowing transaction tracking
Return date monitoring
Query Capabilities
Member-Specific Queries

Current borrowings by member
Overdue books identification
Multi-genre borrower tracking
Inactive member identification
Book-Related Queries

Genre-wise book availability
Most popular books tracking
Available copies monitoring
Analytics

Monthly borrowing statistics
Top member activity tracking
Popular author analysis
Borrowing trends analysis

