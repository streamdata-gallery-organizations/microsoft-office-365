---
swagger: "2.0"
x-collection-name: Microsoft Office 365
x-complete: 0
info:
  title: Microsoft Office 365 Add Folders Folder
  description: You can create a folder by sending a POST request with a JSO...
  version: 1.0.0
host: outlook.office365.com
basePath: /ews/odata/Me
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /AllServices:
    get:
      summary: Get All Services
      description: Get all services.
      operationId: getAllservices
      x-api-path-slug: allservices-get
      responses:
        200:
          description: OK
      tags:
      - Allservices
  /Calendar:
    get:
      summary: Get Calendar
      description: Retrieve information about the default calendar by using the...
      operationId: getCalendar
      x-api-path-slug: calendar-get
      responses:
        200:
          description: OK
      tags:
      - Calendar
  /CalendarGroups:
    get:
      summary: Get Calendar Groups
      description: You can request all the calendar groups in a mailbox (or a f...
      operationId: getCalendargroups
      x-api-path-slug: calendargroups-get
      responses:
        200:
          description: OK
      tags:
      - Calendargroups
    post:
      summary: Add Calendar Groups
      description: You can create a calendar group by sending a POST request wi...
      operationId: postCalendargroups
      x-api-path-slug: calendargroups-post
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Calendargroups
  /CalendarGroups{calendargroup_id}:
    get:
      summary: Get Calendar Groups
      description: Get calendargroups calendargroup
      operationId: getCalendargroupsCalendargroup
      x-api-path-slug: calendargroupscalendargroup-id-get
      responses:
        200:
          description: OK
      tags:
      - Calendargroups
      - Calendargroup
    post:
      summary: Add Calendar Groups
      description: Post calendargroups calendargroup
      operationId: postCalendargroupsCalendargroup
      x-api-path-slug: calendargroupscalendargroup-id-post
      responses:
        200:
          description: OK
      tags:
      - Calendargroups
      - Calendargroup
    delete:
      summary: Delete Calendar Groups
      description: Deleting a calendar group is as simple as sending a DELETE r...
      operationId: deleteCalendargroupsCalendargroup
      x-api-path-slug: calendargroupscalendargroup-id-delete
      responses:
        200:
          description: OK
      tags:
      - Calendargroups
      - Calendargroup
    patch:
      summary: Patch Calendar Groups
      description: You can update a calendar group by sending a PATCH request w...
      operationId: patchCalendargroupsCalendargroup
      x-api-path-slug: calendargroupscalendargroup-id-patch
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Calendargroups
      - Calendargroup
    parameters:
      summary: Parameters Calendar Groups
      description: Parameters calendargroups calendargroup
      operationId: parametersCalendargroupsCalendargroup
      x-api-path-slug: calendargroupscalendargroup-id-parameters
      responses:
        200:
          description: OK
      tags:
      - Calendargroups
      - Calendargroup
  /CalendarGroups{calendargroup_id}/Calendars:
    get:
      summary: Get Calendar Groups Calendars
      description: You can request all the user's calendars (or a filtered list...
      operationId: getCalendargroupsCalendargroupCalendars
      x-api-path-slug: calendargroupscalendargroup-idcalendars-get
      responses:
        200:
          description: OK
      tags:
      - Calendargroups
      - Calendargroup
      - ""
      - Calendars
    post:
      summary: Add Calendar Groups Calendars
      description: You can create a calendar by sending a POST request with a J...
      operationId: postCalendargroupsCalendargroupCalendars
      x-api-path-slug: calendargroupscalendargroup-idcalendars-post
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Calendargroups
      - Calendargroup
      - ""
      - Calendars
    parameters:
      summary: Parameters Calendar Groups Calendars
      description: Parameters calendargroups calendargroup  calendars
      operationId: parametersCalendargroupsCalendargroupCalendars
      x-api-path-slug: calendargroupscalendargroup-idcalendars-parameters
      responses:
        200:
          description: OK
      tags:
      - Calendargroups
      - Calendargroup
      - ""
      - Calendars
  /Calendars{calendar_id}:
    get:
      summary: Get Calendars Calendar
      description: You can also retrieve information about a specific calendar ...
      operationId: getCalendarsCalendar
      x-api-path-slug: calendarscalendar-id-get
      responses:
        200:
          description: OK
      tags:
      - Calendars
      - Calendar
    delete:
      summary: Delete Calendars Calendar
      description: Deleting a calendar is as simple as sending a DELETE request...
      operationId: deleteCalendarsCalendar
      x-api-path-slug: calendarscalendar-id-delete
      responses:
        200:
          description: OK
      tags:
      - Calendars
      - Calendar
    patch:
      summary: Patch Calendars Calendar
      description: You can update a calendar by sending a PATCH request with a ...
      operationId: patchCalendarsCalendar
      x-api-path-slug: calendarscalendar-id-patch
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Calendars
      - Calendar
    parameters:
      summary: Parameters Calendars Calendar
      description: Parameters calendars calendar
      operationId: parametersCalendarsCalendar
      x-api-path-slug: calendarscalendar-id-parameters
      responses:
        200:
          description: OK
      tags:
      - Calendars
      - Calendar
  /Calendars{calendar_id}/Events:
    get:
      summary: Get Calendars Calendar Events
      description: You can request all the events across all calendars (or a fi...
      operationId: getCalendarsCalendarEvents
      x-api-path-slug: calendarscalendar-idevents-get
      responses:
        200:
          description: OK
      tags:
      - Calendars
      - Calendar
      - ""
      - Events
    post:
      summary: Add Calendars Calendar Events
      description: Post calendars calendar  events
      operationId: postCalendarsCalendarEvents
      x-api-path-slug: calendarscalendar-idevents-post
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Calendars
      - Calendar
      - ""
      - Events
    parameters:
      summary: Parameters Calendars Calendar Events
      description: Parameters calendars calendar  events
      operationId: parametersCalendarsCalendarEvents
      x-api-path-slug: calendarscalendar-idevents-parameters
      responses:
        200:
          description: OK
      tags:
      - Calendars
      - Calendar
      - ""
      - Events
  /ContactFolders{contact_folder_id}:
    get:
      summary: Get Contact Folders Contact Folder
      description: You can access the default contact folder by using the const...
      operationId: getContactfoldersContactFolder
      x-api-path-slug: contactfolderscontact-folder-id-get
      responses:
        200:
          description: OK
      tags:
      - Contactfolders
      - Contact
      - Folder
    parameters:
      summary: Parameters Contact Folders Contact Folder
      description: Parameters contactfolders contact folder
      operationId: parametersContactfoldersContactFolder
      x-api-path-slug: contactfolderscontact-folder-id-parameters
      responses:
        200:
          description: OK
      tags:
      - Contactfolders
      - Contact
      - Folder
  /ContactFolders{contact_folder_id}/ChildFolders:
    get:
      summary: Get Contact Folders Contact Folder Childfolders
      description: All non-default contact folders are stored as children of th...
      operationId: getContactfoldersContactFolderChildfolders
      x-api-path-slug: contactfolderscontact-folder-idchildfolders-get
      responses:
        200:
          description: OK
      tags:
      - Contactfolders
      - Contact
      - Folder
      - ""
      - Childfolders
    parameters:
      summary: Parameters Contact Folders Contact Folder Childfolders
      description: Parameters contactfolders contact folder  childfolders
      operationId: parametersContactfoldersContactFolderChildfolders
      x-api-path-slug: contactfolderscontact-folder-idchildfolders-parameters
      responses:
        200:
          description: OK
      tags:
      - Contactfolders
      - Contact
      - Folder
      - ""
      - Childfolders
  /ContactFolders{contact_folder_id}/Contacts:
    get:
      summary: Get Contact Folders Contact Folder Contacts
      description: You can request all contacts (or a filtered set by using the...
      operationId: getContactfoldersContactFolderContacts
      x-api-path-slug: contactfolderscontact-folder-idcontacts-get
      responses:
        200:
          description: OK
      tags:
      - Contactfolders
      - Contact
      - Folder
      - ""
      - Contacts
    post:
      summary: Add Contact Folders Contact Folder Contacts
      description: You can create a contact by sending a POST request with a JS...
      operationId: postContactfoldersContactFolderContacts
      x-api-path-slug: contactfolderscontact-folder-idcontacts-post
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contactfolders
      - Contact
      - Folder
      - ""
      - Contacts
    parameters:
      summary: Parameters Contact Folders Contact Folder Contacts
      description: Parameters contactfolders contact folder  contacts
      operationId: parametersContactfoldersContactFolderContacts
      x-api-path-slug: contactfolderscontact-folder-idcontacts-parameters
      responses:
        200:
          description: OK
      tags:
      - Contactfolders
      - Contact
      - Folder
      - ""
      - Contacts
  /Contacts{contact_id}:
    get:
      summary: Get Contacts Contact
      description: You can retrieve information about a specific contact by usi...
      operationId: getContactsContact
      x-api-path-slug: contactscontact-id-get
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Contact
    post:
      summary: Add Contacts Contact
      description: You can create a contact by sending a POST request with a JS...
      operationId: postContactsContact
      x-api-path-slug: contactscontact-id-post
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Contact
    delete:
      summary: Delete Contacts Contact
      description: You can delete a contact by simply sending a DELETE request ...
      operationId: deleteContactsContact
      x-api-path-slug: contactscontact-id-delete
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Contact
    patch:
      summary: Patch Contacts Contact
      description: To update a contact, send a PATCH request to the URL of the ...
      operationId: patchContactsContact
      x-api-path-slug: contactscontact-id-patch
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Contact
    parameters:
      summary: Parameters Contacts Contact
      description: Parameters contacts contact
      operationId: parametersContactsContact
      x-api-path-slug: contactscontact-id-parameters
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Contact
  /Contacts{contact_id}/Attachments:
    get:
      summary: Get Contacts Contact Attachments
      description: To get attachments, send a GET request to the Attachments pr...
      operationId: getContactsContactAttachments
      x-api-path-slug: contactscontact-idattachments-get
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Contact
      - ""
      - Attachments
    post:
      summary: Add Contacts Contact Attachments
      description: To add an attachment to an item, send a POST request to the ...
      operationId: postContactsContactAttachments
      x-api-path-slug: contactscontact-idattachments-post
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Contact
      - ""
      - Attachments
    delete:
      summary: Delete Contacts Contact Attachments
      description: To delete an attachment, send a DELETE request to the URL of...
      operationId: deleteContactsContactAttachments
      x-api-path-slug: contactscontact-idattachments-delete
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Contact
      - ""
      - Attachments
    parameters:
      summary: Parameters Contacts Contact Attachments
      description: Parameters contacts contact  attachments
      operationId: parametersContactsContactAttachments
      x-api-path-slug: contactscontact-idattachments-parameters
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Contact
      - ""
      - Attachments
  /Events{event_id}:
    get:
      summary: Get Events Event
      description: You can also retrieve information about a specific event by ...
      operationId: getEventsEvent
      x-api-path-slug: eventsevent-id-get
      responses:
        200:
          description: OK
      tags:
      - Events
      - Event
    delete:
      summary: Delete Events Event
      description: Upon success, the appointment is moved to the user's Deleted...
      operationId: deleteEventsEvent
      x-api-path-slug: eventsevent-id-delete
      responses:
        200:
          description: OK
      tags:
      - Events
      - Event
    patch:
      summary: Patch Events Event
      description: To update an event, send a PATCH request to the URL of the e...
      operationId: patchEventsEvent
      x-api-path-slug: eventsevent-id-patch
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Events
      - Event
    parameters:
      summary: Parameters Events Event
      description: Parameters events event
      operationId: parametersEventsEvent
      x-api-path-slug: eventsevent-id-parameters
      responses:
        200:
          description: OK
      tags:
      - Events
      - Event
  /Events{event_id}/Accept:
    post:
      summary: Add Events Event Accept
      description: Post events event  accept
      operationId: postEventsEventAccept
      x-api-path-slug: eventsevent-idaccept-post
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Events
      - Event
      - ""
      - Accept
    parameters:
      summary: Parameters Events Event Accept
      description: Parameters events event  accept
      operationId: parametersEventsEventAccept
      x-api-path-slug: eventsevent-idaccept-parameters
      responses:
        200:
          description: OK
      tags:
      - Events
      - Event
      - ""
      - Accept
  /Events{event_id}/Decline:
    post:
      summary: Add Events Event Decline
      description: Post events event  decline
      operationId: postEventsEventDecline
      x-api-path-slug: eventsevent-iddecline-post
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Events
      - Event
      - ""
      - Decline
    parameters:
      summary: Parameters Events Event Decline
      description: Parameters events event  decline
      operationId: parametersEventsEventDecline
      x-api-path-slug: eventsevent-iddecline-parameters
      responses:
        200:
          description: OK
      tags:
      - Events
      - Event
      - ""
      - Decline
  /Events{event_id}/TentativelyAccept:
    post:
      summary: Add Events Event Tentatively Accept
      description: Post events event  tentativelyaccept
      operationId: postEventsEventTentativelyaccept
      x-api-path-slug: eventsevent-idtentativelyaccept-post
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Events
      - Event
      - ""
      - Tentativelyaccept
    parameters:
      summary: Parameters Events Event Tentatively Accept
      description: Parameters events event  tentativelyaccept
      operationId: parametersEventsEventTentativelyaccept
      x-api-path-slug: eventsevent-idtentativelyaccept-parameters
      responses:
        200:
          description: OK
      tags:
      - Events
      - Event
      - ""
      - Tentativelyaccept
  /FirstSignIn:
    get:
      summary: Get Firstsignin
      description: Get firstsignin
      operationId: getFirstsignin
      x-api-path-slug: firstsignin-get
      responses:
        200:
          description: OK
      tags:
      - Firstsignin
  /Folders{folder_id}:
    get:
      summary: Get Folders Folder
      description: You can retrieve information about other folders by using th...
      operationId: getFoldersFolder
      x-api-path-slug: foldersfolder-id-get
      responses:
        200:
          description: OK
      tags:
      - Folders
      - Folder
    post:
      summary: Add Folders Folder
      description: You can create a folder by sending a POST request with a JSO...
      operationId: postFoldersFolder
      x-api-path-slug: foldersfolder-id-post
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Folders
      - Folder
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---