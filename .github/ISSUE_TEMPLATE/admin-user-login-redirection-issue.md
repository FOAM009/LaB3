---
name: Admin/User Login Redirection Issue
about: Report an issue about Admin/User Login.
title: "[BUG] Login/Register Account Path Issue"
labels: ''
assignees: FOAM009

---

name: Admin/User Login Redirection Issue
description: Report an issue about Admin/User Login.
title: "[Auth] Admin/User Login Issue"
labels: ["authentication", "frontend"]

body:
  - type: textarea
    id: description
    attributes:
      label: "📌 Issue Details"
      description: "Explain the issue about user role redirection."
      placeholder: "Describe the issue here..."
    validations:
      required: true

  - type: dropdown
    id: role
    attributes:
      label: "👤 User Role"
      description: "Which user role is affected?"
      options:
        - Admin
        - User
        - Both
    validations:
      required: true
