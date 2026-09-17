# SIH-1710
## NAME: NITHYASRI T
## REGISTER NO:212225220068
## Smart India Hackathon Workshop
## Problem Statement ID: SIH 1710
## Problem Title

Enhancing Navigation for Railway Station Facilities and Locations

## Problem Creator's Organization

Ministry of Railways

## Problem Description

Large railway stations contain multiple platforms, entrances, ticket counters, waiting halls, restrooms, food courts, lifts, escalators and other facilities.

Passengers who are unfamiliar with the station may find it difficult to locate their destination within a short period of time.

The problem becomes more difficult for elderly passengers, visually impaired passengers and passengers who require step-free routes.

A smart indoor navigation system is therefore required to help passengers find facilities and platforms through simple and accessible directions.

## Idea
1. QR-Based Starting Location

QR codes are placed at important locations such as entrances, ticket counters and platform areas.

When a passenger scans a QR code, the system identifies the corresponding station location and uses it as the starting point for navigation.

## 2. Smart Facility Search

Passengers can search for:

Platforms
Ticket counters
Restrooms
Food courts
Waiting halls
Lifts
Escalators
Exits
Help desks

The system displays the selected facility and the route to reach it.

## 3. Accessibility-Aware Navigation

Passengers can select navigation preferences such as:

Avoid stairs
Prefer lifts
Prefer ramps
Shortest route
Accessible route

The system generates a route according to the selected preference.

## 4. Live Facility Status

Station administrators can update the availability of facilities.

For example:

Lift 1 – Available

Lift 2 – Under Maintenance

Platform Entrance – Temporarily Closed

The navigation system avoids unavailable routes and suggests alternatives.

## 5. Voice Guidance

The application provides voice instructions during navigation.

This can assist passengers who have difficulty continuously viewing the screen.

## 6. Kiosk-to-Mobile Navigation

Digital kiosks can be installed at important locations.

A passenger can select the destination on the kiosk and scan a generated QR code to continue the same route on their mobile phone.

## Proposed Solution

RailGuide is a multi-platform indoor railway navigation system consisting of a mobile application, digital kiosks, a station navigation database and an administrator dashboard.

## Basic Workflow
Passenger
    ↓
Mobile App / Digital Kiosk
    ↓
Scan QR / Select Starting Point
    ↓
Search Destination
    ↓
Select Navigation Preference
    ↓
Navigation Engine
    ↓
Check Station Map + Facility Status
    ↓
Generate Route
    ↓
Visual + Voice Directions
    ↓
Destination
Proposed Solution Architecture
+-----------------------------+
|        USER INTERFACE       |
| Mobile App | Digital Kiosk  |
+-------------+---------------+
              |
              ↓
+-----------------------------+
|     LOCATION IDENTIFIER     |
| QR Code / Selected Landmark |
+-------------+---------------+
              |
              ↓
+-----------------------------+
|      NAVIGATION ENGINE      |
| Route Calculation           |
| Accessibility Filtering     |
| Alternative Route           |
+-------------+---------------+
              |
              ↓
+-----------------------------+
|       STATION DATABASE      |
| Maps | Facilities | Routes  |
| Platforms | Accessibility  |
+-------------+---------------+
              |
              ↓
+-----------------------------+
|     ADMIN DASHBOARD         |
| Facility Updates            |
| Route Updates               |
| Temporary Closures          |
+-----------------------------+
## Use Cases
Passenger
Search for a facility
Select destination
Scan QR code
View station map
View route
Receive navigation instructions
Accessibility User
Select accessible navigation
Avoid stairs
Prefer lifts and ramps
Use voice guidance
Kiosk User
Search destination
View route
Select accessibility preference
Transfer route to mobile
Station Administrator
Update station map
Add or modify facilities
Update facility availability
Mark routes as temporarily unavailable

## Technology Stack
## Frontend
React.js
HTML
CSS
JavaScript
## Backend
Node.js
Express.js
## Database
Firebase / PostgreSQL
## Navigation
Graph-based route calculation
Indoor station map
## Additional Technologies
QR Code Scanner
Text-to-Speech
Web-based Admin Dashboard
Git & GitHub
## Dependencies
## Station Data

Station maps, facilities and route information are required.

## QR Infrastructure

QR codes need to be placed at selected station landmarks.

## Navigation Data

The system requires connectivity information between station locations.

## Administrative Updates

A station administrator is required to update temporary closures and facility availability.

## Expected Benefits
Reduces passenger confusion inside large stations.
Helps passengers locate facilities quickly.
Provides accessible route options.
Supports visually impaired passengers through voice guidance.
Provides an alternative route when a facility or path is unavailable.
Connects physical station locations with digital navigation.
Allows navigation to continue from a kiosk to a mobile device.
