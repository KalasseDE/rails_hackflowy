# Hackflowy - Rails Edition

**Author**: Duke Nguyen

**Repository**: https://github.com/dukeraphaelng/rails_hackflowy



_____



### Features

**Landing Page (if not logged in)**

- Sign up
- Log in



**User Page (if logged in)**

- Header
  - Directory Hamburger Menu
    - All Home Dot Points
  - Setting Hamburger Menu
    - Dot Points
      - Posts
      - Undo
      - Redo
      - Save
      - Print
      - Export All
    - Account Setting
      - Account
        - Name
        - Email
        - Password
      - Appearance
        - Theme
        - Font
      - Other
        - Keyboard shortcuts
          - Zoom in/out
          - Expand/collapse
          - Indent/outdent
          - Move up/down
          - Add note
          - Complete
          - Duplicate
          - Delete
          - Search
          - Show/hide completed
          - Star page
          - Bold
          - Italic
          - Underline
        - Email summaries of changes to account
      - Experimental features
      - Delete my account
    - Help
    - Report a Problem
    - Log Out
      user_account.email
  - Show completed
  - Search
- Body
  All capabilities in keyboard shortcuts



____



### Implementation Plan

#### **Essential**

- CRUD Paragraph
  - Create paragraph (on Enter at the end of the line)
  - Edit paragraph
  - Delete paragraph
  - Save paragraph
- Indent/outdent paragraphs
- Expand/collapse
- Zoom in/out



#### Step 1

- Real-time Features
  *Using either Socket.io or better [Action Cable](https://blog.heroku.com/real_time_rails_implementing_websockets_in_rails_5_with_action_cable) & [Web Socket](https://www.ably.io/blog/rails-actioncable-the-good-and-the-bad)*
  - Undo
  - Redo
  - Save



#### **Step 2**

- Add note
- Complete
- Duplicate
- Star page



#### Step 3

- Search
- Show/hide completed
- Change text-decoration (bold, italics, underline)



#### Step 4

- Print
- Export All



#### Step 5

- Landing Page

- CRUD Account
  - Create
  - Edit
  - Delete
- Account Features
  - Name
  - Email
  - Password
- Account Capabilities
  - Sign Up
  - Sign In
  - Sign Out



#### Step 6

- All Home Dot Points
- Change Default Theme & Font
- Help
- Report a Problem

