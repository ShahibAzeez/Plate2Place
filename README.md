# Plate2Place

### From Surplus Plates to Purposeful Places

Plate2Place is an AI-powered food rescue and redistribution platform that connects food donors, NGOs, shelters, and volunteers through a centralized real-time ecosystem. The platform helps reduce food waste by ensuring surplus edible food reaches people in need before it expires.

---

## Overview

Food wastage and food insecurity continue to coexist despite the availability of surplus edible food.

Restaurants, cafeterias, hotels, bakeries, grocery stores, and hostels frequently dispose of usable food due to the absence of an efficient redistribution mechanism.

Plate2Place addresses this challenge by enabling food donors to publish available food, intelligently matching donations with nearby NGOs, coordinating volunteer pickups, and tracking the complete delivery lifecycle.

---

## Problem Statement

Large quantities of edible food are discarded every day while many shelters, NGOs, and underserved communities face food shortages.

Existing donation processes rely heavily on:

- Phone calls
- Messaging groups
- Manual coordination
- Spreadsheets

These methods lack scalability, transparency, tracking, and real-time decision-making.

---

## Proposed Solution

Plate2Place provides a technology-driven platform that streamlines the food donation process through:

- Real-time donation posting
- Intelligent NGO matching
- Volunteer coordination
- Live delivery tracking
- AI-powered decision support
- Impact measurement and reporting

---

## Key Features

### Donation Management

- Create and manage food donations
- Upload food details and images
- Specify quantity and expiry window
- Track donation lifecycle

### NGO Management

- Browse available donations
- Accept or decline requests
- Manage organizational capacity
- Monitor incoming deliveries

### Volunteer Management

- View assigned tasks
- Access optimized routes
- Confirm pickups and deliveries
- Monitor delivery history

### Administration Panel

- User management
- Donation monitoring
- NGO verification
- Platform analytics

### Real-Time Tracking

- Live status updates
- Route monitoring
- Delivery progress tracking
- Activity notifications

---

## Artificial Intelligence Features

### Food Classification

Analyzes uploaded food images and automatically identifies food categories.

### Expiry Risk Assessment

Evaluates urgency levels based on food type, quantity, and available donation windows.

### Smart NGO Matching

Matches donations using:

- Distance
- Capacity
- Current demand
- Food compatibility
- Urgency level

### AI Insights Engine

Provides recommendations and operational insights to improve donation efficiency.

### Rescue Score System

Measures impact based on:

- Donation quantity
- Delivery efficiency
- Beneficiary reach
- Urgency handled

Generates leaderboards for:

- Top Donors
- Top NGOs
- Top Volunteers

---

## User Roles

### Food Donor

Organizations contributing surplus food.

### NGO / Shelter

Organizations receiving and distributing donated food.

### Volunteer

Individuals responsible for pickup and delivery operations.

### Administrator

Platform management and monitoring.

---

## System Workflow

```text
Food Donor
    │
    ▼
Create Donation
    │
    ▼
AI Analysis
    │
    ▼
Smart NGO Matching
    │
    ▼
Volunteer Assignment
    │
    ▼
Pickup Confirmation
    │
    ▼
Delivery Tracking
    │
    ▼
Food Delivered
    │
    ▼
Impact Dashboard Updated
```

---

## System Architecture

```text
                  ┌──────────────────────┐
                  │      Frontend        │
                  │  Next.js + React     │
                  └──────────┬───────────┘
                             │
                             ▼
                  ┌──────────────────────┐
                  │     Backend API      │
                  │   Node.js + Express  │
                  └──────────┬───────────┘
                             │
        ┌────────────────────┼────────────────────┐
        │                    │                    │
        ▼                    ▼                    ▼
┌─────────────┐    ┌────────────────┐   ┌────────────────┐
│  MongoDB    │    │   AI Engine    │   │   Socket.IO    │
│  Database   │    │  OpenAI API    │   │ Real-Time Sync │
└─────────────┘    └────────────────┘   └────────────────┘
        │                    │                    │
        └────────────────────┼────────────────────┘
                             │
                             ▼
                 ┌────────────────────────┐
                 │ Maps & Tracking Layer  │
                 │ Leaflet + OpenStreetMap│
                 └────────────────────────┘
```

---

## Technology Stack

### Frontend

- Next.js
- React
- TypeScript
- Tailwind CSS
- ShadCN UI

### Backend

- Node.js
- Express.js

### Database

- MongoDB

### Artificial Intelligence

- OpenAI API

### Real-Time Communication

- Socket.IO

### Maps & Tracking

- Leaflet
- OpenStreetMap

### Analytics

- Recharts

### Deployment

- Vercel

---

## Project Structure

```bash
app/
├── page.tsx
├── donate/
├── auth/
├── dashboard/
├── ngo/dashboard/
├── volunteer/dashboard/
├── admin/dashboard/
├── map/
├── chat/
├── analytics/
└── api/

components/
├── site-shell.tsx
├── dashboard-shell.tsx
├── live-map.tsx
├── donation-form.tsx
├── theme-provider.tsx
├── brand-mark.tsx
└── dashboard/
    ├── stat-card.tsx
    ├── donation-card.tsx
    ├── donations-list.tsx
    └── ai-insights.tsx

lib/
├── types.ts
├── seed-data.ts
├── demo-store.ts
├── use-demo-store.ts
├── ai.ts
└── api.ts

server/
├── index.js
├── models/
├── routes/
└── middleware/
```

---

## Impact Metrics

The platform tracks:

- Total Food Rescued
- Meals Served
- Active NGOs
- Active Volunteers
- Successful Deliveries
- Food Waste Prevented
- Estimated Carbon Emissions Reduced

---

## Future Roadmap

### Phase 1
- Core donation platform
- Real-time tracking
- NGO matching

### Phase 2
- Mobile application
- Multi-city deployment
- Advanced analytics

### Phase 3
- Government integration
- Smart logistics optimization
- Predictive donation forecasting

### Phase 4
- National food rescue network
- Carbon impact reporting
- Food safety verification system

---

## Team Contributions

| Team Member | Responsibility |
|------------|---------------|
| Member 1 | Frontend Development & UI/UX |
| Member 2 | Backend Development & Database |
| Member 3 | Artificial Intelligence & Matching Engine |
| Member 4 | Maps, Analytics & Real-Time Services |

---

## Vision

To create a scalable food rescue ecosystem that minimizes food waste, improves food accessibility, and empowers communities through technology-driven coordination and intelligent decision-making.

---

## Conclusion

Plate2Place transforms surplus food into meaningful impact through intelligent matching, real-time coordination, and measurable outcomes.

By connecting donors, NGOs, volunteers, and administrators on a single platform, Plate2Place creates a sustainable and scalable approach to food redistribution.

**Plate2Place — From Surplus Plates to Purposeful Places**Places.
Built for a hunger-free India.
