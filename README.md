PURPOSE: This is a web app for the collection and modification of events, including event details and attendees.

CURRENT STATE: The app is currently able to collect and delete event and event category data and sync with database. It does not yet handle attendees.

FUTURE: Need to add Person class and code to collect data, add to event, and edit.
  Proposed additions:
  1. Person Class Fields: Name, Id, Email, ContactId (to tie to ContactInfo class in answer 2), Role
	    Person Class Methods: Constructor, Add, UpdateRole, ToString override
  2. Other Classes: ContactInfo with Address, Phone Number, etc.
		  Roles with options like EventCategory for person's role in event
  3. Person-Event: Many to Many
	    Person-Role: Many to One
	    Person-ContactInfo: One to One
