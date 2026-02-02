# Strapi
a leading open-source, Node.js-based headless Content Management System (CMS) that allows developers to build fast, customizable APIs (REST or GraphQL) for websites and mobile apps.
# Strapi Project Setup

This repository contains a local Strapi project with a sample content type. The project demonstrates how to set up Strapi, create a collection type, and manage content.

---

## Table of Contents
- [Project Setup](#project-setup)
- [Running Strapi Locally](#running-strapi-locally)
- [Project Folder Structure](#project-folder-structure)
- [Admin Panel](#admin-panel)
- [Creating a Sample Content Type](#creating-a-sample-content-type)
- [Testing the API](#testing-the-api)
- [Additional Notes](#additional-notes)

---

## Project Setup

1. Clone the Strapi repository:

```bash
git clone https://github.com/strapi/strapi.git
cd strapi
npm install
npm run develop
The server will start at http://localhost:1337
Access the Admin Panel at http://localhost:1337/admin.

You’ll need to create an admin user on first login
Project Folder Structure

api/ → Contains your collection types and API endpoints

components/ → Reusable components for your content types

config/ → Project configuration (database, server, plugins)

public/ → Static files

extensions/ → Plugin customizations

package.json → Project dependencies and scripts
Admin Panel

Content Manager → Manage entries of your collection types

Media Library → Store and manage media files (images, videos, etc.)

Content-Type Builder → Create and edit collection types and single types

Settings → Configure roles, permissions, and project settings
Creating a Sample Content Type

Collection Type: BlogPost
Fields Added:

Field Name	Field Type	Notes
title	Text (Short)	Required
content	Rich Text (Blocks)	Required
cover_image	Media	Optional
published_date	Date	Optional
Steps Taken:

Go to Content-Type Builder → Click Create new collection type

Fill in Display Name → BlogPost

Add fields listed above

Click Save and wait for Strapi to restart
