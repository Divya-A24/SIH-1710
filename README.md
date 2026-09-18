# Smart India Hackathon Workshop

## Date:

18:09:2026

## Register Number:

212225230063

## Name:

Divya A

---

## Problem Title

**SIH 1710: Enhancing Navigation for Railway Station Facilities and Locations**

---

## Problem Description

Railway stations are large and complex places containing many facilities such as platforms, ticket counters, restrooms, food courts, waiting halls, lifts, escalators and enquiry counters. Passengers, especially first-time visitors, senior citizens and people with disabilities, may face difficulties in finding these facilities.

The proposed solution is a **smart railway station navigation system** that helps passengers locate facilities and destinations easily. It provides interactive maps, real-time directions, voice-guided navigation and accessibility-friendly routes.

The system will be accessible through **mobile applications and digital kiosks** installed inside railway stations. It will also support regular updates when platform locations, facilities or routes change.

---

## Problem Creater's Organization

**Ministry of Railways, Government of India**

---

## Idea

1. **Smart Facility Locator:** Help passengers find platforms, ticket counters, restrooms, food courts, waiting halls, lifts, escalators and other facilities.

2. **Interactive Navigation:** Provide an interactive station map with step-by-step directions from the passenger's current location to the selected destination.

3. **Accessibility Mode:** Provide wheelchair-friendly routes, lift-based routes and routes that avoid stairs for passengers with accessibility requirements.

4. **Voice-Guided Navigation:** Provide voice instructions to assist visually impaired passengers while navigating inside the station.

5. **Digital Kiosk:** Provide touch-screen kiosks where passengers can search for facilities, view routes and scan a QR code to continue navigation on their mobile phones.

6. **Real-Time Updates:** Allow railway administrators to update platform changes, blocked routes, facility availability and changes in station layout.

7. **Emergency Assistance:** Help passengers locate emergency exits, medical centres, security offices and help desks.

---

## Proposed Solution / Architecture Diagram

```text
                  USER
                   |
          +--------+--------+
          |                 |
       MOBILE             KIOSK
          |                 |
          +--------+--------+
                   |
             USER INTERFACE
                   |
          NAVIGATION SYSTEM
                   |
       +-----------+-----------+
       |                       |
 STATION DATABASE         MAP SERVICE
       |                       |
       +-----------+-----------+
                   |
             ROUTE ENGINE
                   |
          Dijkstra / A* Algorithm
                   |
       +-----------+-----------+
       |                       |
 VOICE NAVIGATION       ACCESSIBILITY
       |                       |
       +-----------+-----------+
                   |
            ADMIN DASHBOARD
                   |
           REAL-TIME UPDATES
```

---

## Use Cases

### Passenger

* Search for railway station facilities
* View interactive station map
* Find the nearest facility
* Get step-by-step directions
* Use voice navigation
* Select an accessible route
* Find emergency services

### Visually Impaired Passenger

* Enable voice navigation
* Receive spoken directions
* Find accessible facilities
* Navigate independently using audio instructions

### Senior Citizen / Wheelchair User

* Select accessibility mode
* Avoid stairs
* Find lifts and ramps
* Get wheelchair-friendly routes

### Railway Administrator

* Add or remove facilities
* Update facility locations
* Update platform information
* Mark routes as blocked
* Update station maps
* Manage real-time information

### Kiosk User

* Select destination
* Search facilities
* View station map
* Get navigation instructions
* Scan QR code to continue navigation on mobile

---

## Technology Stack

**Frontend:**

* React.js
* JavaScript
* HTML
* CSS

**Backend:**

* Node.js
* Express.js

**Database:**

* PostgreSQL / Firebase

**Maps & Navigation:**

* Google Maps API
* Indoor Station Maps
* Dijkstra / A* Algorithm

**Voice Assistance:**

* Web Speech API
* Text-to-Speech

**Authentication:**

* Firebase Authentication

**Development Tools:**

* Git
* GitHub
* Postman / Insomnia

**Deployment:**

* Vercel
* Render / Firebase

---

## Dependencies

**Mapping Service – 10 Days**
Integration of interactive station maps and navigation services.

**Station Data Collection – 10 Days**
Collection of information about platforms, facilities, entrances, exits, lifts and routes.

**Navigation Module – 10 Days**
Implementation of shortest-path and accessibility-based route calculation.

**Voice Navigation – 7 Days**
Integration of voice-guided instructions for visually impaired passengers.

**Digital Kiosk – 10 Days**
Development of a touch-friendly kiosk interface for railway stations.

**Real-Time Update System – 7 Days**
Implementation of facility, platform and route updates.

**Testing & Deployment – 7 Days**
Testing navigation accuracy, accessibility, responsiveness and system performance.

**Estimated Budget: ₹50,000**
