# Kohler Digital Catalog iOS App

A production iOS application for browsing and managing product catalogs and project-based shopping lists with full offline and online support.

## Overview

The Kohler iOS App provides an intuitive experience for exploring product catalogs, creating projects and shopping lists, adding notes, and exporting data. It is designed with an offline-first architecture to ensure reliable access even without network connectivity.

## Access Notice

This repository is a read-only showcase of a production application developed for a company.  
Source code cannot be made public due to confidentiality and intellectual property restrictions.

## Features

### Region-Based Catalogs
- Interactive region selection
- Region-specific products, pricing, and availability
- Clickable regions within catalog pages
- Region-based notes and shopping list integration 

### Search & Filtering
- Global and advanced search with filters (brand, category, price range)  
- Popular search suggestions for faster access  
- Navigate directly to specific pages from search results  

### Project & Shopping Lists
- Create and manage multiple projects  
- Add products to shopping lists with quantities and notes  
- Track project history and export data as PDF or Excel  
- Offline access to saved projects and shopping lists  

### Notes & Annotations
- Add and customize notes on catalog regions  
- Save notes for future reference  

### Pricing
- Display product prices with multi-price support and discount calculations  

### Catalog Browsing
- Dynamic catalog layouts with grids, carousels, and custom sections  
- Supports both portrait and landscape orientations  
- Thumbnail view and table of contents for quick navigation  

### Online & Offline Support
- Automatic network detection  
- Online mode with real-time catalog updates, downloads, and data sync  
- Offline mode with cached catalogs, shopping lists, projects, and notes
- Data synchronization: offline changes queued and synced automatically when network is available   

## Tech Stack

- Swift  
- UIKit  
- Core Data  
- REST APIs  
- PDFKit  
- RangeSeekSlider  

## Architecture

- MVC architecture with ViewModel layer for business logic  
- ViewControllers and Storyboards for catalog viewing, project management, search, and bookmarks  
- Models for Catalog, Region, Project, Shopping List, and Notes  
- Core Data and LocalDataStore for offline storage and state management  
- Data flow: API → Models → ViewModels → Views  
- Smooth navigation between screens with dual orientation support  
- Catalog regions and PDF/Excel export for product information   

## Key Contributions

- Built a production-grade iOS catalog application with offline-first support 
- Implemented project-based shopping lists with export options  
- Enabled region-based notes and annotations  
- Developed reliable online/offline data synchronization using Core Data  
- Optimized state management using singleton pattern (LocalDataStore)  
- Enhanced user experience with smooth transitions, thumbnail navigation, and dual orientation support
