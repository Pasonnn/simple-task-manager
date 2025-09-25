# Task Manager App - Learning Frappe REST API

This is a simple task management application built with Frappe Framework to learn the fundamentals of Frappe's REST API, authentication, permissions, and backend development concepts.

## 🎯 Project Overview

A mini version of Trello/Asana built on Frappe to practice:

- User Authentication (session-based and token-based API)
- DocType creation and relationships
- Built-in REST API usage
- Custom API endpoints
- Role-based permissions
- Background jobs (optional)

## 🏗️ Architecture

### DocTypes

- **Project** → Simple project with name and description
- **Task** → Belongs to a project, has status (Open, In Progress, Done), due date, assigned user
- **Comment** (optional) → Linked to tasks for practicing child tables

### API Endpoints

- Auto-generated CRUD endpoints: `/api/resource/Project`, `/api/resource/Task`
- Custom endpoint: `/api/method/task_manager.api.get_my_tasks`

## 🚀 Setup Instructions

### 1. Install Frappe Environment
