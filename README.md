# Strapi Internship Task 1 – Local Setup

## Objective
The objective of this task is to set up Strapi locally, explore its project structure, start the admin panel, create a sample content type, and document the complete process as part of the internship training.

---

## Tech Stack
- Node.js (v20)
- Strapi (Community Edition)
- SQLite (default database)
- Git & GitHub

---

## Task Steps Performed

### 1. Clone the Strapi Repository
The official Strapi GitHub repository was cloned to explore the Strapi framework and understand its structure.

```bash
git clone https://github.com/strapi/strapi
```
>Note: The Strapi repository is a monorepo containing the framework source code.
>To run Strapi locally as an application, the Strapi CLI is used.

### 2. Create and Run Strapi Application Locally

A new Strapi application was created using the official Strapi CLI with the quickstart option.
```bash
npx create-strapi@latest . --quickstart
```
This command:
- Sets up a complete Strapi application
- Uses SQLite as the default database
- Starts the development server automatically

### 3. Start Admin Panel
After successful setup, the Strapi admin panel was accessed at:
```bash
http://localhost:1337/admin
```
An admin user was created and the dashboard was verified successfully.

### 4. Create Sample Content Type
A sample collection type named Article was created using the Content-Type Builder with the following fields:
```text
Field Name	Type
title	Text
description	Rich Text
publishedDate	Date
```

### 5. Create Sample Entry
A sample entry was created and published using the Content Manager to verify that the content type and database are working correctly.

### 6. Explore Project Folder Structure
The key folders of the Strapi project were explored:
```text
src/api/        → APIs and content types
config/         → Application and database configuration
database/       → Database setup (SQLite)
public/         → Static assets
```
The created content type is available under:
```text
src/api/article
```

---

## How to Run the Project Locally
```bash
npm install
npm run develop
```

Admin Panel:
```bash
http://localhost:1337/admin
```

---

## Submission Details
- GitHub repository contains the Strapi application setup
- A separate branch was created for this task
- Pull Request raised from task branch to main branch
- Loom video recorded explaining the setup and workflow

---

## Loom Video

A walkthrough video demonstrating the Strapi local setup, admin panel, content type creation, and pull request:
- https://www.loom.com/share/1c0440671bdf4e3db26fa9b61d49c7ba

---

## Author
Jaspal Gundla
