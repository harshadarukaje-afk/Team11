Problem Statement: College Event Management System Feature Set: 
1.Participant Details:
Name:Harshada rukaje 
Roll Number:U15CZ26S0061
Class:BCA Ist year ‘B’
2. Event Details
3. Registration
4. Event Date
5. Registration Status
​
Promt: Create a simple, clear,step-by-step algorithm flowchart and ER Diagram with requirements for the following assignment.
Problem Statement: College Event Management System Feature Set:
1. Participant Details
2. Event Details
3. Registration
4. Event Date
5. Registration Status

REQUIRMENT FOR ALGORITHM:
- Start the College Event Management System.
- Enter and store participant details such as Participant ID, Name, Contact Number and Email.
- Enter and store event details such as Event ID, Event Name and Event Date.
- Allow a participant to register for an event.
- Store the registration details.
- Check and display the registration status such as Registered, Pending or Cancelled.
- Display the participant, event, registration, event date and registration status details.
- End the process.
Requirements for Flowchart:
- The flowchart must represent the complete process from START to STOP.
- Include input of participant details.
- Include input of event details.
- Include event date.
- Include participant registration.
- Check whether the registration is successful.
- If successful, set/display status as Registered.
- If not successful, show Pending/Cancelled.
- Display the participant details, event details, event date, registration details and registration status.
- Use standard flowchart symbols:
  - Oval → Start/Stop
  - Parallelogram → Input/Output
  - Rectangle → Process
 - Diamond → Decision
  - Arrow → Flow direction


Requirements for ER Diagram:
   PARTICIPANT
- Participant_ID (Primary Key)
- Participant_Name
- Contact_No
- Email
EVENT
- Event_ID (Primary Key)
- Event_Name
- Event_Date
REGISTRATION
- Registration_ID (Primary Key)
- Participant_ID (Foreign Key)
- Event_ID (Foreign Key)
- Registration_Date
- Registration_Status

Relationships:
- A participant can register for one or more events.
- An event can have one or more participants.
- The REGISTRATION entity connects PARTICIPANT and EVENT.
- Clearly show the relationship between the entities.
- Clearly mark Primary Keys (PK) and Foreign Keys (FK).
- Show the correct cardinality, such as 1:M / M:N, wherever appropriate.

Diagram Requirements:
- Use standard ER diagram notation.
- Rectangle → Entity
- Oval → Attribute
- Diamond → Relationship
- Underline or clearly mark primary keys.
- Keep the diagram simple, neat and easy to understand.
- Do not add unnecessary entities or attributes.
- Make it suitable for a 1st-year BCA college assignment.
