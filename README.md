# Automated Meeting Scheduler

An end-to-end scheduling workflow that integrates Google Forms, Google Calendar, and Gmail to automatically generate calendar events and send instant client confirmations upon form submission.

##  Architecture & Workflow
<img width="863" height="424" alt="image" src="https://github.com/user-attachments/assets/6a333a98-b00c-46d7-bcae-0f6985aa6b36" />

**Modules Used:**
* Google Forms (Trigger)
* Google Calendar (Event Creation)
* Gmail (Automated Communication)

##  How It Works
1. **Trigger:** A client submits a "Meeting Request" form with their name, email, and topic.
2. **Scheduling:** Make.com automatically creates a new event on the host's Google Calendar for the requested time.
3. **Confirmation:** A formatted confirmation email is instantly sent to the client via Gmail, confirming the scheduled time and topic.

##  Business Value
* Eliminates manual back-and-forth emails for scheduling.
* Prevents double-booking and scheduling errors.
* Provides instant, professional client communication.

##  How to Import
1. Log in to your [Make.com](https://www.make.com/) account.
2. Create a new Scenario.
3. Click the menu (three dots) in the top right -> **Import blueprint**.
4. Upload the `blueprint.json` file from this repository.
5. Re-authenticate your Google account connections and ensure your Google Calendar ID is set to your primary email.
