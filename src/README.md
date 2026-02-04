# Mergington High School Activities

A web application built with FastAPI and MongoDB that allows students to view and sign up for extracurricular activities at Mergington High School.

## Features

### For Students
- **View Activities**: Browse all available extracurricular activities with detailed information
- **Search**: Search activities by name or description
- **Filter Activities**: Filter by multiple criteria including:
  - Category (Sports, Arts, Academic, Community, Technology)
  - Day of the week (Monday through Sunday, including weekends)
  - Time of day (Before School, After School, Weekend)
  - Difficulty level (Beginner, Intermediate, Advanced, All Levels)
- **Activity Details**: View comprehensive information for each activity:
  - Description and schedule
  - Available spots and current participants
  - Difficulty level
  - Category tag
- **Registration**: Sign up for activities (requires teacher authentication)
- **Share Activities**: Share activity information via social media or email
- **Dark Mode**: Toggle between light and dark themes

### For Teachers
- **Authentication**: Secure login system for teachers
- **Student Management**: 
  - Register students for activities
  - Remove students from activities
  - View participant lists

## Technology Stack

- **Backend**: FastAPI (Python web framework)
- **Database**: MongoDB (for storing activities and teacher accounts)
- **Frontend**: HTML, CSS, JavaScript
- **Authentication**: Password hashing with Argon2

## For Teachers: Requesting Changes

Not comfortable with code? No problem! Use our [Issue Templates Guide](../docs/issue-templates-guide.md) to learn how to request changes using simple forms.

## Development Guide

For detailed setup and development instructions, please refer to our [Development Guide](../docs/how-to-develop.md).
