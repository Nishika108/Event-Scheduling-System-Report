Objective

The objective of this project is to design and implement
an Event Scheduling System in C++ that efficiently
manages events, their schedules, and participant lists.
The system supports functionalities such as adding,
deleting, and searching for events, managing
participants using event ID, and checking for schedule
conflicts. Additionally, the system handles event
reminders using priority queues.
Introduction

An Event Scheduling System is a vital tool for
organizing and managing events, ensuring that all
details are properly coordinated and that participants
are kept informed.
This project aims to create a menu-based application in
C++ that allows users to efficiently manage events and
participants. The system uses various data structures,
including a balanced tree, vectors, and priority queues
to achieve its goals.

Key Features

Add Event: Allows users to add new events with details
such as name, date, and time.

3

Delete Event: Enables users to delete existing events
based on the date and time.

Search Event: Provides functionality to search for
events based on the date and time.

Add Participant: Lets users add participants to specific
events.

List Participants: Displays the list of participants for
a specific event.
Check Schedule Conflict: Checks for any schedule
conflicts for a given date and time.
Handle Reminders: Manages event reminders and notifies
users about upcoming events.
Modules

The Event Scheduling System is divided into several
modules, each responsible for specific functionalities.
These modules interact with each other to provide a
seamless user experience.
➢ Event Structure:
The Event structure holds the details of an event,
including its name, date, time, and a list of
participants.
Attributes:
• name: The name of the event.
• date: The date of the event in YYYY-MM-DD format.
• time: The time of the event in HH:MM format.
• participants: A vector of strings storing the names
of participants.

4
➢ EventSchedulingSystem Class:
The EventSchedulingSystem class is the core
component of the system, managing all operations
related to events and participants.
Attributes:
• events: A map that stores events, keyed by a
combination of date and time.
• reminders: A priority queue that handles event
reminders, sorted by event dates.
Methods:
• addEvent: Adds a new event to the system.
• deleteEvent: Deletes an existing event from the
system.
• searchEvent: Searches for an event based on the date
and time.
• addParticipant: Adds a participant to a specific
event.
• listParticipants: Lists all participants for a
specific event.
• checkScheduleConflict: Checks for schedule conflicts
for a given date and time.
• handleReminders: Handles event reminders and
notifies users about upcoming events.
• menu: Provides a menu-based interface for user
interaction.

➢ User Interface:
The system provides a simple, text-based user
interface through a menu-driven approach, allowing
users to select various options to manage events and
participants.
