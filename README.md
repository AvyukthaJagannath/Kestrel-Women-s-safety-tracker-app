# Kestrel-Women's-safety-tracker-app
Problem
Standard navigation apps route users purely on speed, often directing people walking home alone—especially at night—through dark, isolated streets. Existing safety apps rely on manual panic buttons or timers that fail if a phone is dropped, powered off, or taken.

Solution
Kestrel is an automated personal safety and navigation web app. It replaces shortest-path algorithms with safety-weighted routing based on street lighting and open 24/7 stores, while using geofenced arrival detection to verify safe arrivals automatically.

Key Features
Safety-Weighted Navigation: Prefers well-lit routes and active commercial areas over dark side streets.

Geofenced Arrival Detection: Automatically ends tracking sessions when the user comes within 30 meters of their destination (no timers required).

Server-Side Failsafe: Acts as a "dead-man switch." If connection drops or movement stops unexpectedly without a safe check-in, the server automatically triggers emergency SMS alerts.

Anomalous Stoppage Pings: Detects extended mid-route stops and prompts quick check-ins.

Tech Stack
Frontend: HTML, CSS, JavaScript, Leaflet.js, Browser Geolocation API

Backend: Python (Flask)

Integrations: Twilio API (SMS Alerts), WebSockets / HTTP Fetch
