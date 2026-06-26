# ManageLife
Managing Life Easier with my projects
Manage my Damn Life (MMDL) is a self hosted front end for managing your CalDAV tasks and calendars.

This project is in beta state, so be careful if you're working with production data.
Features
Manage your CalDAV tasks.
Supports sub tasks.
Supports many fields like due, status, description, recurrence, and more
Manage calendar events.
Supports multiple CalDAV accounts, and multiple user accounts.
View your tasks as a list, in a gantt view, or on a calendar.
Create and manage task filters to view your tasks as you see fit.
"Reponsive-ish" view. This is a desktop first project, as multiple clients like JTX Boards, OpenTasks exist for mobile.
OAUTH support
Planned features
Support all fields for VTODO and VEVENT as described in RFC 5545.
More flexible ways to view tasks, and customisable views.
Drag and drop capability for tasks
Ability to create external plugins.
Compatibility
This client has been tested with Nextcloud, Radicale, and Baikal. MMDL uses "tsdav" library for CalDAV access, so it should support all servers supported by tsdav.

MMDL also supports OAuth authentication for CalDAV Accounts. As of now, Google Calendars is supported. To get started, checkout the guide here.
