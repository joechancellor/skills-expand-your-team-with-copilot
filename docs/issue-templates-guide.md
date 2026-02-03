# Using Issue Templates for Change Requests

## For Teachers: How to Request Changes

This guide explains how to request changes to the Mergington High School Activities website without needing to write code yourself.

### What Are Issue Templates?

Issue templates are simple forms that help you describe what you need changed on the website. When you fill out a form, it creates a "ticket" that can be assigned to someone (or GitHub Copilot) to make the changes for you.

### How to Create an Issue

1. **Go to the Issues tab** in the GitHub repository
2. **Click "New Issue"** button
3. **Choose the template** that matches what you need
4. **Fill out the form** with all the requested information
5. **Click "Submit new issue"**

That's it! The issue will be automatically assigned to help you get your changes made.

### Available Templates

We've created several templates for common tasks:

#### 🎯 Add New Activity
Use this when you want to add a new extracurricular activity to the website.

**What you'll need to provide:**
- Activity name
- Category (Sports, Arts, Academic, Community, Technology)
- Description
- Teacher/advisor name
- Meeting days and times
- Location
- Difficulty level
- Maximum number of participants

**Example use case:** "I want to add a new Robotics Club that meets on Tuesdays and Thursdays"

---

#### ✏️ Modify Activity Details
Use this when you need to change information about an existing activity.

**What you'll need to provide:**
- Which activity to modify
- What fields need to change
- The new values
- Reason for the change

**Example use case:** "Drama Club moved to a different room and changed its meeting time"

---

#### 🗑️ Remove Activity
Use this when an activity is no longer offered.

**What you'll need to provide:**
- Activity name
- Reason for removal
- Confirmation that you understand the impact
- Optional: Replacement activity suggestion

**Example use case:** "Chess Club is cancelled due to low enrollment"

---

#### 🎨 UI or Design Change
Use this when you want to change how the website looks.

**What you'll need to provide:**
- Which part of the website to change
- Type of change (colors, layout, text size, etc.)
- How it looks now
- How you want it to look
- Reason for the change

**Example use case:** "Make the activity cards use the school colors (blue and gold)"

---

#### 🐛 Bug Report
Use this when something isn't working correctly.

**What you'll need to provide:**
- Description of the problem
- Steps to reproduce the issue
- What should happen instead
- How serious the problem is
- How often it happens

**Example use case:** "When I click the Sign Up button, nothing happens"

---

#### ✨ Feature Request
Use this when you want to add new functionality.

**What you'll need to provide:**
- Description of the new feature
- Why it's needed
- How it should work
- Who would use it
- How important it is

**Example use case:** "Add the ability for students to add activities to their personal calendar"

---

#### 📝 Content Update
Use this when you need to change text or messages on the website.

**What you'll need to provide:**
- Where the content is located
- Current text (exact copy)
- New text (exact replacement)
- Reason for change

**Example use case:** "Change 'Register' button to say 'Sign Up'"

---

## Tips for Writing Good Issues

### Be Specific
Instead of: "The website needs to look better"
Try: "Change the activity cards to use school colors: blue (#003366) and gold (#FFD700)"

### Include Details
The more information you provide, the faster changes can be made. Use all the fields in the template.

### One Issue Per Request
If you need multiple unrelated changes, create separate issues for each one. This makes it easier to track progress.

### Provide Examples
If you've seen something similar on another website or have a specific vision, mention it!

## What Happens Next?

1. **Automatic Assignment**: Your issue will be automatically assigned to GitHub Copilot or a team member
2. **Implementation**: The changes will be made to the code
3. **Review**: You may be asked to review and approve the changes
4. **Completion**: The issue will be closed when the work is done

## Need Help?

If you're not sure which template to use or need assistance, you can:
- Ask a colleague who has used the system before
- Create a general issue describing what you need
- Contact the technical support team

---

## For Technical Staff

### Template Structure

Each template includes:
- **Clear Problem Description**: User-friendly form fields
- **Acceptance Criteria**: Specific conditions that must be met
- **Implementation Hints**: Technical guidance for developers
- **Technical Context**: Information about the codebase
- **Limitations**: Constraints and boundaries

### Modifying Templates

Templates are located in `.github/ISSUE_TEMPLATE/`. Each is a YAML file following GitHub's issue form schema.

To add or modify templates:
1. Edit the relevant `.yml` file in `.github/ISSUE_TEMPLATE/`
2. Test the YAML syntax
3. Commit and push changes
4. Templates update automatically on GitHub

### Template Guidelines

When creating or modifying templates:
- Use clear, non-technical language for user-facing fields
- Provide examples and placeholders
- Include comprehensive implementation notes for Copilot
- Specify acceptance criteria clearly
- Note any technical limitations or constraints
