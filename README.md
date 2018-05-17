# Mindful Reflection Website

**How to Use?**

- Option 1: Use URL: https://agile-dawn-44507.herokuapp.com
- Option 2: Copy the repo and run npm start on the 'server' and 'reflection' directory

**Demo User:**  

Email: lang@sina.com  

Password: P123456

# What is this application?

A single page application which can help you to remember important information, such as class notes, and solutions of algorithm problem etc.  It has the following functions:

- Register
- Login
- Add/Edit/Delete notes
- Sync notes to the backend database (DynamoDB) 
- Review notes on a pre-defined interval (1, 2, 7 30 days)
  For example, if you created a note today, you can see this note in the 'Review' mode so that you review and remember it. 

# Why does it help to remember stuff?

- There is no full stream based, cross-platform tool in the market which can help us to remember meaningful notes (in Evernote) even though there are some partly working tools in the market like Anki, Revunote, and Reflect.
- Be proud of building a meaningful project to solve a real-life problem

The theory to remember stuff in a long-term is based on Space Repetition and Active Practicing.

- Wiki Spaced Repetition
- "Are You Using Evernote All Wrong? An Introduction to Spaced Repetition for Rapid Learning"

- What is Spaced Repetition?
- Evernote's Spaced Repetition

# Who make this application?

- Ann @annlearnerLi
- Bin @ishibin
- Boqun @zhangbq5858

Here are the **roles and assignments.**

- Login page @Ann
- Test and enhance UI @Ann
- Data operations(input, edit, delete, update) @Boqun
- Settled review cycle @Boqun
- Metadata and data model design @Bin
- Deploy and integrate code @Bin

# Directory Structure

.

├── design

├── reflection

│   ├── public

│   └── src

└── resource

# More

- Code: source code
- Wiki: meeting notes
- Projects: tasks management
- Issues: bugs and enhancement

---

# History and Changes

2018-03-28: Use local persistent data storage (database) instead of Evernote API in order to practice what we've learned in the class.

2018-04-01: Setup the folder Directory Structure

2018-04-23: Deploy to Heroku.
