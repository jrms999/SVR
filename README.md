# SVR
SVR app


SVR Residents Hub – Concept Overview

Working title: SVR Residents Hub
Purpose: A simple, secure mobile app that supports day-to-day life for residents of Whitefoord House, Rosendael and Bellrock Close by making support easier to reach and information easier to find.

1. The problem

Residents of Scottish Veterans Residences often juggle:

Finding the right person to speak to about housing, benefits, health, or personal issues.

Remembering appointment times and events.

Reporting repairs through paper or word-of-mouth, which can be hard to track.

Navigating external services (NHS, veterans’ charities, benefits) with limited digital support.

Staff, in turn, spend a lot of time:

Answering repeated questions (“Who do I talk to about X?”).

Manually logging and tracking repairs and support requests.

Disseminating urgent information (changes to benefits, weather alerts, building issues).

We can ease this burden with a simple digital tool built around how veterans actually live in SVR accommodation.

2. The solution: SVR Residents Hub

A cross-platform mobile app (iOS & Android) plus a secure staff dashboard, designed specifically for SVR, that acts as a central “Support Hub” for each residence.

Core MVP features

For residents:

Today at SVR (Home screen)

Today’s meals, activities and events.

Quick actions: Contact Support, Report a Repair, View My Appointments.

Support Requests

Simple form to ask for help with: benefits/money, housing issues, mental health & wellbeing, employment, or “other”.

Option to indicate urgency and preferred contact (in-person, phone, message).

Residents can see their own history and status: new → in progress → closed.

Maintenance / Repair Requests

Easy way to report non-emergency faults (heating, plumbing, electrical, furniture, etc.), including location and (later) photos.

Residents can see whether a request has been received and what stage it’s at.

Announcements & Events

Residence-specific announcements: fire drills, weather warnings, changes to benefits support, social events.

Events list with date, time and location for activities, workshops, and meetings.

Resource Library

Curated, easy-to-browse list of key links and documents (NHS, Combat Stress, Veterans Gateway, benefits guidance, employment support).

Can be tailored per residence and updated centrally by staff.

For staff:

Staff dashboard (web)

View and manage all support and maintenance requests, filterable by residence and status.

Post announcements and events to specific residences or all residents.

Maintain the resource library (links, PDFs, contact details).

Light reporting

Basic metrics on number of requests, average time to close, and app usage.

Helps demonstrate impact and inform service planning.

3. Benefits

For residents

Clear, low-stress way to ask for help and know they’ve been heard.

Reduced confusion over who to speak to and how.

Better awareness of what’s happening in their residence and community.

A tool they can carry in their pocket as they transition towards more independent living.

For staff and SVR as an organisation

Less time spent on repetitive admin and chasing information – more time on meaningful support.

Simple, consistent way to log and track repairs and support interactions.

Better communication in emergencies or when things change quickly.

Data to support funding bids, reporting and continuous improvement.

4. Approach & technology

Co-designed with residents & staff: We start with short interviews and on-site testing to make sure the app is accessible, non-intimidating and genuinely useful.

Lightweight technology stack:

Resident app built once and deployed on both iOS and Android.

Secure API and database hosted on modern, low-cost cloud infrastructure.

Staff dashboard accessible via any web browser with appropriate permissions.

Security & privacy:

UK GDPR-compliant data handling, encrypted connections, role-based access.

Minimal personal data stored, and only what’s necessary to deliver the service.

5. What’s needed from SVR

To move from idea to pilot, we would ask for:

A small steering group of 2–3 staff and 3–5 residents across different residences to shape the design.

Access for discovery: permission to run a short discovery phase (interviews, workshops) to understand day-to-day needs and current processes.

A pilot site: e.g. one residence (or a single floor / group) for a 6–12 week pilot of the app.

Feedback loop: agreement on how we collect feedback and iterate (e.g. short surveys, monthly check-in with staff).

With these in place, we can rapidly build a simple but meaningful first version and prove its value in the real world before scaling to all SVR sites.



Backend (FastAPI)

main.py

Folder structure ready for you to paste in the full backend code we generated

Basic health endpoint included

✔️ Frontend (React Native / Expo)

App.tsx skeleton

Folder structure:

src/screens/auth/
