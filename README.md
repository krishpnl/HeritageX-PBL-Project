# Smart Tourism & Cultural Heritage Discovery Platform

> A digital platform for discovering heritage, culture, local experiences, and tourism destinations through a modern and intelligent web interface.

**Project Type:** B.Tech Computer Engineering — PBL Project  
**Project Status:** 🚧 Frontend Development & Backend Integration Pending

---

## 📌 Overview

The **Smart Tourism & Cultural Heritage Discovery Platform** is a web-based tourism platform designed to provide users with a centralized place to discover historical locations, cultural heritage, traditional arts, handicrafts, local food, festivals, heritage walks, nearby attractions, and other cultural experiences.

Tourists often depend on multiple platforms to find information about destinations, historical significance, routes, timings, local experiences, and nearby attractions. This project aims to bring these different aspects together into a single, user-friendly platform.

The system is designed to support **digital tourism, cultural heritage preservation, responsible tourism, and local community visibility**, while contributing to the vision of **Viksit Bharat @2047** and relevant Sustainable Development Goals (SDG 8, SDG 11, and SDG 12).

---

## 🎯 Objectives

- Provide easy access to heritage and historical destinations.
- Organize accurate and meaningful heritage information.
- Recommend destinations based on user interests, location, distance, and available time.
- Promote local communities, artisans, traditional food, and cultural experiences.
- Create awareness about cultural heritage preservation.
- Encourage responsible and sustainable tourism.
- Provide map-based discovery and route information.
- Support trip and itinerary planning.
- Provide an administration system for managing and verifying heritage information.

---

## ✨ Key Features

### 🏛️ Heritage Discovery

Users can explore heritage destinations with information such as:

- Heritage site name
- Category
- Description
- Historical background
- Cultural significance
- Architecture
- Images
- Location
- Distance
- Visiting information
- Ratings
- Responsible tourism guidelines

### 🔎 Search & Filtering

Users can find relevant destinations using:

- Keyword search
- Heritage category
- User interests
- Location
- Distance
- Ratings
- Available time

### 🤖 Smart Recommendations

The planned recommendation system considers:

```text
User Interests
      ↓
Nearby Heritage Places
      ↓
Remove Incompatible Places
      ↓
Consider Available Time
      ↓
Prioritize Relevant Places
      ↓
Recommended Destinations
```

The system is designed to provide explainable recommendations, such as:

> *Suggested because you selected History and this heritage site is nearby.*

### 🗺️ Map Explorer

The platform provides map-based exploration for discovering heritage locations and nearby attractions.
Planned capabilities include:

- Heritage markers
- Location information
- Distance calculation
- Nearby places
- Route information
- Trip planning

### 🧭 Trip Planner

Users can create an ordered travel itinerary based on selected destinations.
The system can consider:

- Selected places
- Location
- Distance
- Available time
- Estimated visit duration
- Route order

### ❤️ Saved Places

Users can save interesting destinations for future reference.
The current frontend may use browser storage for this functionality until backend integration is completed.

### ⭐ Ratings & Reviews

Users can provide:

- Ratings
- Reviews
- Feedback

The backend will eventually handle review storage, validation, moderation, and management.

### 🎭 Culture & Heritage

The platform covers cultural elements beyond monuments, including:

- Traditional food
- Festivals
- Arts
- Handicrafts
- Local markets
- Cultural practices
- Heritage stories
- Local experiences

### 🚶 Heritage Walks

A dedicated section is planned for curated heritage walking experiences, routes, and important cultural locations.

---

## 🛠️ Technology Stack

### Frontend

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Website structure |
| **CSS3** | Styling and responsive design |
| **JavaScript** | Dynamic functionality |
| **Bootstrap 5** | Responsive UI components |
| **Bootstrap Icons** | Interface icons |
| **Chart.js** | Dashboard analytics |
| **Leaflet** | Interactive maps |
| **OpenStreetMap** | Map data |

### Backend

Backend development and API integration are handled separately.
The final backend is expected to provide:

- REST APIs
- Authentication
- Authorization
- Business logic
- Data validation
- Recommendation logic
- Database integration

### Database

The database technology will be finalized as part of backend development.

---

## 📂 Project Structure

```text
Heritage-PBL/
│
├── index.html
│
├── pages/
│   ├── explore.html
│   ├── recommendations.html
│   ├── map.html
│   ├── itinerary.html
│   ├── culture.html
│   ├── heritage-walks.html
│   ├── saved.html
│   └── ...
│
├── admin/
│   ├── login.html
│   ├── dashboard.html
│   ├── ...
│   │
│   ├── css/
│   │   └── ...
│   │
│   └── js/
│       └── ...
│
├── css/
│   └── ...
│
├── styles/
│   ├── data.js
│   ├── main.js
│   └── ...
│
└── README.md
```

---

## 🔌 Backend Integration

This repository contains the frontend implementation and is intended to be handed over to the backend developer for API and database integration.

### Expected Backend Flow

```text
Authentication
       ↓
User Profile & Preferences
       ↓
Heritage Catalogue
       ↓
Search & Filtering
       ↓
Recommendation Engine
       ↓
Locations & Maps
       ↓
Trip Planning
       ↓
Saved Places
       ↓
Ratings & Reviews
       ↓
Administration
```

### Expected Backend Modules

- User Authentication
- User Profiles
- User Preferences
- Heritage Sites
- Categories
- Cultural Information
- Recommendations
- Locations
- Itineraries
- Saved Places
- Reviews & Ratings
- Heritage Walks
- Admin Management
- Heritage Verification
- Analytics

---

## 🗄️ Planned Data Entities

The backend may require entities such as:

- `User`
- `HeritageSite`
- `Category`
- `Review`
- `Rating`
- `SavedPlace`
- `Itinerary`
- `Recommendation`
- `Culture`
- `HeritageWalk`
- `Admin`

---

## 🤝 Frontend → Backend Handoff

Before implementing the backend APIs, the backend developer should review:

- Existing HTML pages
- JavaScript files (`data.js`, `main.js`)
- Form fields and element IDs
- Existing data structures
- Search and filtering logic requirements
- Recommendation inputs
- Map-related coordinates and attributes
- Itinerary builder requirements
- Review moderation requirements
- Admin panel functionality

---

## 🔐 Admin Panel & Security Notes

The project includes an administrative interface for managing platform content.

### Proposed Capabilities
- Add / Edit / Delete heritage sites
- Heritage verification workflows
- Review moderation
- System and category analytics

### ⚠️ Security Warning
The current frontend admin authentication is intended only for development/prototype purposes. Frontend-only authentication and browser storage must not be considered production-grade security.

For production deployment, the backend should implement:
- Server-side authentication (JWT / secure session tokens)
- Secure password hashing (bcrypt / argon2)
- Role-based access control (RBAC)
- Strict server-side input validation and sanitization
- API authentication and rate limiting
- Secure database connection pooling and protection

---

## 🚧 Development Status

| Module | Status |
| :--- | :---: |
| Project Research | ✅ Completed |
| Requirements | ✅ Completed |
| Project Scope | ✅ Completed |
| UML Design | ✅ Completed |
| UI/UX Design | 🟡 In Progress |
| Frontend Development | 🟡 In Progress |
| Heritage Catalogue | 🟡 In Progress |
| Search & Filtering | 🟡 Frontend Done |
| Recommendations | 🟡 Prototype |
| Map Explorer | 🟡 Frontend Done |
| Trip Planner | 🟡 Frontend Done |
| Reviews & Ratings | 🟡 Frontend Done |
| Admin Dashboard | 🟡 Prototype |
| Backend API | 🔴 Pending |
| Database | 🔴 Pending |
| Production Authentication | 🔴 Pending |
| Full Integration | 🔴 Pending |
| Final Testing | 🔴 Pending |

### Status Legend
- ✅ Completed
- 🟡 In Progress / Prototype
- 🔴 Pending

---

## 🏗️ Target System Architecture

```text
┌──────────────────────────────────────┐
│              FRONTEND                │
│        HTML / CSS / JavaScript       │
│             Bootstrap 5              │
└──────────────────┬───────────────────┘
                   │
                REST API
                   │
┌──────────────────▼───────────────────┐
│              BACKEND                 │
│ Authentication                       │
│ Authorization                        │
│ Business Logic                       │
│ Recommendation Engine                │
│ Validation                           │
└──────────────────┬───────────────────┘
                   │
┌──────────────────▼───────────────────┐
│              DATABASE                │
│ Users                                │
│ Heritage Sites                       │
│ Reviews                              │
│ Analytics                            │
└──────────────────────────────────────┘
```

---

## 📍 Initial Scope

### Included in Version 1.0
- Heritage discovery & details
- Search and multi-criteria filtering
- Smart recommendations
- Map explorer with markers
- Itinerary & trip planning
- Ratings and reviews
- Cultural articles and heritage walks
- Administration dashboard

### Not Included in Initial Version
- Online ticket booking
- Online payment processing
- Complete offline navigation
- Full Augmented Reality (AR) tours

---

## 🌱 Project Vision

The long-term vision is to create a scalable digital platform connecting:
**Tourists + Heritage + Local Communities + Culture + Technology**

The platform aims to improve the visibility of cultural heritage, encourage responsible tourism, support local communities, and contribute to the preservation of cultural knowledge for future generations.

---

## ⚠️ Development Disclaimer

This repository currently represents a development-stage frontend application. Some features use static data, mock data, browser storage, or frontend-only logic for development and demonstration purposes. The application should not be considered production-ready until backend integration, database implementation, authentication, authorization, validation, API security, testing, and deployment are completed.

---

## 👨‍💻 Project Details

- **Academic Program:** B.Tech Computer Engineering — PBL Project
- **Domain:** Smart Tourism & Cultural Heritage (HeritageX)
- **Link For Frontend:** https://heritage-x.netlify.app/
- **Theme:** Digital Tourism and Cultural Heritage Preservation
- **Vision:** Viksit Bharat @2047
- **Related SDGs:** SDG 8 (Decent Work and Economic Growth), SDG 11 (Sustainable Cities and Communities), SDG 12 (Responsible Consumption and Production)

---

## 👥 Contributors

**B.Tech Computer Engineering — PBL Project Team**
- Frontend Development
- Backend Development
- Database Development
- UI/UX Design
- Research & Documentation
- Testing & Integration

---

## 📄 License

This project is currently developed for academic and PBL purposes. License and usage terms can be added when the project is finalized.

---

*Smart Tourism & Cultural Heritage Discovery Platform — Discover Heritage. Experience Culture. Travel Smarter.*
