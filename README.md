# Degree Planner Skill Tree

A web application designed to streamline the process of planning and managing a student's academic journey. This tool simplifies course planning while providing real-time feedback on graduation progress.

## Project Summary

The Degree Planner Skill Tree addresses the inefficiencies and frustrations students face when organizing their coursework, such as juggling multiple tabs, manually checking prerequisites, and tracking degree progress. By integrating course data, degree requirements, and user-friendly features, this tool makes academic planning more efficient and less error-prone.

## The Problem

Planning classes for a degree can be:
- Clunky and time-consuming, requiring multiple tools and tabs
- Error-prone, as students must manually verify prerequisites and track requirements
- Overwhelming, with no centralized way to explore courses, track progress, or evaluate options like electives or emphasis areas

## The Solution

The Degree Planner Skill Tree offers a centralized, interactive platform for students to:
- Browse Courses: Explore available classes with detailed information (descriptions, prerequisites, average GPA, best professors, syllabus links)
- Plan Semesters: Drag and drop courses into semester slots while checking difficulty levels and graduation requirements
- Track Progress: Get real-time updates on degree completion status with visual indicators (green/yellow/red) for each requirement
- Customize Plans: Create structured or blank degree plans tailored to individual needs, including emphasis areas and electives

## Key Features

- **Course Word Bank**: A searchable catalog of available courses with hover-over details like descriptions, GPA stats, professor ratings (from RateMyProfessors), and syllabus links
- **Drag-and-Drop Semester Planner**: Intuitive interface for organizing courses into semesters
- **Degree Progress Tracker**: Visual sidebar that dynamically updates based on completed and planned courses
- **Difficulty Metrics**: Semester difficulty scores calculated using GPA data from ANEX
- **Customizable Plans**: Options for structured (predefined templates) or blank plans with manual emphasis area selection
- **Course Catalog Browsing**: Filterable course lists specific to the user's major

## Target Audience

The primary users are undergraduate students who want a more efficient way to plan their academic journey while ensuring they stay on track for graduation.

## Technical Requirements

### Stack
- Backend: Python (Flask), SQLAlchemy ORM
- Database: MySQL
- Frontend: HTML5, JavaScript, CSS (Tailwind CSS)

### Core Functionalities
- User authentication (Flask-Login or Flask-JWT)
- Course database with integrated prerequisite checks and professor ratings
- Drag-and-drop semester planning interface
- Real-time degree progress tracking

### Security
- HTTPS/TLS encryption
- CSRF protection (Flask-WTF)
- Input validation to prevent SQL injection/XSS attacks
- Secure session management

### Data Sources
- ANEX for GPA data and difficulty metrics
- University course catalog for course descriptions and requirements
- RateMyProfessors for professor ratings

## MVP Scope

The Minimum Viable Product (MVP) focuses on:
- User registration/login with saved degree plans
- A working course browser with hover-over details
- Basic semester planning with drag-and-drop functionality
- Real-time degree progress tracking for a predefined CSCE degree plan

## Long-Term Vision

The Degree Planner Skill Tree aims to become an indispensable tool for students by expanding its capabilities to include:
- Advanced features like conflict detection, "What If" scenarios, and shareable plans
- Support for mobile platforms (React Native)
- Integration with multiple institutions' degree plans

This project is about creating an intuitive, all-in-one solution that empowers students to take control of their academic journey while reducing stress and complexity in the planning process.
