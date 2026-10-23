# SOSA Business Card Scanner

An OCR-based application for extracting contact information from business card images and organizing the extracted information for digital use and Excel-based sales workflows.

> **Project Status:** In Development

## Overview

The Business Card Scanner is designed to reduce the manual effort involved in entering contact information from physical business cards.

The application processes a business card image, extracts relevant information using Optical Character Recognition (OCR), and structures the extracted information for further use.

The workflow is designed to support both contact creation and Excel-based lead management.

## Key Features

* Business card image scanning
* OCR-based text extraction
* Extraction and structuring of contact details
* Export of extracted information to Excel
* Add extracted contacts to phone contacts
* Add data to a new Excel spreadsheet
* Add data to an existing Excel spreadsheet
* Easy sharing of extracted information with sales teams

## Application Workflow

```text
Business Card Image
        ↓
   OCR Processing
        ↓
   Text Extraction
        ↓
Information Structuring
        ↓
   ┌───────────────┐
   │               │
Contacts        Excel
   │               │
Phone Contact   New / Existing Sheet
```

## Tech Stack

* **Python**
* **OCR**
* **React** — frontend interface
* **Excel / Spreadsheet Integration**

Additional libraries and implementation details will be documented as development progresses.

## How It Works

### 1. Scan Business Card

The user provides an image of a physical business card.

### 2. Extract Text

OCR processing identifies and extracts the text present on the card.

### 3. Structure Information

The extracted text is processed and organized into relevant fields such as:

* Name
* Company
* Job Title
* Phone Number
* Email
* Website
* Address

### 4. Choose an Action

The structured information can then be used to:

* Create a phone contact
* Add the information to a new Excel spreadsheet
* Add the information to an existing Excel spreadsheet

### 5. Share and Manage

The Excel-based workflow makes it easier to share collected contacts with sales teams and maintain a centralized list of leads.

## Use Case

The application is intended for individuals and sales teams who regularly collect business cards and need a faster way to digitize and organize contact information.

Instead of manually entering contact details from each business card, the application automates the initial extraction and structuring process.

## Project Status

The application is currently in development, with the core OCR and data-processing workflow being implemented alongside the frontend interface and export functionality.

The project is being refined toward a complete end-to-end workflow from business card scanning to contact or spreadsheet export.

## Planned Improvements

* Improve OCR accuracy across different business card layouts
* Add validation and editing before export
* Improve extraction of phone numbers, emails, and websites
* Support multiple business cards in a batch
* Improve Excel formatting and data organization
* Complete and refine the React-based interface
* Add additional contact-management and export options

## Demo

A demonstration video and live demo will be added once the application reaches a stable release.

## Author

**Neeraj Anemajal**
