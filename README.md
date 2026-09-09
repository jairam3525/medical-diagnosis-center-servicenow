# Medical Diagnostic Center – ServiceNow

A ServiceNow-based Medical Diagnostic Center application designed to manage diagnostic tests, patient appointments, test approvals, and lab reports through a structured workflow.

## Overview

The Medical Diagnostic Center provides a complete workflow for managing medical diagnostic tests.

Patients can browse available tests, book appointments, and access their reports. Administrators can manage diagnostic tests, review appointments, approve tests, and complete the workflow.

The project is developed as a **Scoped ServiceNow Application** with a focus on workflow automation, data management, and user-friendly interfaces.

## Key Features

- Diagnostic test catalog
- Test search and category filtering
- Patient appointment booking
- Appointment approval workflow
- Appointment status management
- Automated email notifications
- Lab report generation
- Patient-specific report access
- Role-based access and application security
- Custom ServiceNow portal interface

## Core Tables

### Diagnostic Test
Maintains the diagnostic tests available at the Medical Diagnostic Center, including test name, code, category, description, price, duration, and availability.

### Appointment
Stores patient booking information and manages the appointment workflow from booking through completion.

### Report
Stores generated lab reports for completed diagnostic appointments.

### Patient
Maintains patient information with a unique patient record associated with each user.

## Application Scope

The project is developed within a **private application scope**, providing application-level isolation and security from other ServiceNow applications.

## Technology Stack

- ServiceNow
- ServiceNow Studio
- JavaScript
- GlideRecord
- ServiceNow Client Scripts
- ServiceNow Server Scripts
- Service Portal
- HTML
- CSS
- AngularJS
- ServiceNow Flow/Workflow concepts

## Project Workflow

```text
Patient
   ↓
Browse Diagnostic Tests
   ↓
Book Test
   ↓
Appointment Created
   ↓
Administrator Reviews
   ↓
Appointment Approved
   ↓
Test Completed
   ↓
Lab Report Generated
   ↓
Patient Views Report