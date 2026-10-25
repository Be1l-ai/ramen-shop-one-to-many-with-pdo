# Ramen Shop - One-to-Many with PDO

## Background

This repository contains the midterm activity for the **Application Development** subject, focusing on **One-to-Many Relationships** and **PDO (PHP Data Objects)**.

### Project Overview
A simple ramen shop management system demonstrating:
- **One-to-Many Relationship**: Shops → Menu Items (one shop can have many menu items)
- **PDO**: Secure database interactions using prepared statements
- **CRUD Operations**: Create, Read, Update, Delete for both shops and menu items

### Features
- Shop management (add, edit, delete ramen shops)
- Menu management (add, edit, delete menu items per shop)
- Database schema with proper foreign key constraints
- Seed data for testing

### Database Structure
- **shops** table: id, name, location, contact, created_at
- **menu_items** table: id, shop_id (FK), name, description, price, category, created_at
