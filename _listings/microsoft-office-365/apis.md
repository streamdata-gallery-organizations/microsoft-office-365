---
name: Microsoft Office 365
x-slug: microsoft-office-365
description: Integrate Office 365 REST APIs powered by Microsoft Graph into your own
  app to connect to files, calendars, mail and more.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Microsoft Office 365
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft Office 365 Get All Services
  x-api-slug: microsoft-office-365
  description: Get all services.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//AllServices
  tags: Allservices
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/allservices-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/allservices-get-openapi.md
- name: Microsoft Office 365 Get Calendar
  x-api-slug: microsoft-office-365
  description: Retrieve information about the default calendar by using the...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Calendar
  tags: Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendar-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendar-get-openapi.md
- name: Microsoft Office 365 Get Calendar Groups
  x-api-slug: microsoft-office-365
  description: You can request all the calendar groups in a mailbox (or a f...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//CalendarGroups
  tags: Calendargroups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendargroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendargroups-get-openapi.md
- name: Microsoft Office 365 Add Calendar Groups
  x-api-slug: microsoft-office-365
  description: You can create a calendar group by sending a POST request wi...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//CalendarGroups
  tags: Calendargroups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendargroups-post-openapi.md
- name: Microsoft Office 365 Get Calendar Groups
  x-api-slug: microsoft-office-365
  description: Get calendargroups calendargroup
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//CalendarGroups{calendargroup_id}
  tags: Calendargroups, Calendargroup
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendargroupscalendargroup-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendargroupscalendargroup-id-get-openapi.md
- name: Microsoft Office 365 Add Calendar Groups
  x-api-slug: microsoft-office-365
  description: Post calendargroups calendargroup
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//CalendarGroups{calendargroup_id}
  tags: Calendargroups, Calendargroup
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendargroupscalendargroup-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendargroupscalendargroup-id-post-openapi.md
- name: Microsoft Office 365 Delete Calendar Groups
  x-api-slug: microsoft-office-365
  description: Deleting a calendar group is as simple as sending a DELETE r...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//CalendarGroups{calendargroup_id}
  tags: Calendargroups, Calendargroup
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendargroupscalendargroup-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendargroupscalendargroup-id-delete-openapi.md
- name: Microsoft Office 365 Patch Calendar Groups
  x-api-slug: microsoft-office-365
  description: You can update a calendar group by sending a PATCH request w...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//CalendarGroups{calendargroup_id}
  tags: Calendargroups, Calendargroup
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendargroupscalendargroup-id-patch-openapi.md
- name: Microsoft Office 365 Parameters Calendar Groups
  x-api-slug: microsoft-office-365
  description: Parameters calendargroups calendargroup
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//CalendarGroups{calendargroup_id}
  tags: Calendargroups, Calendargroup
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendargroupscalendargroup-id-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendargroupscalendargroup-id-parameters-openapi.md
- name: Microsoft Office 365 Get Calendar Groups Calendars
  x-api-slug: microsoft-office-365
  description: You can request all the user's calendars (or a filtered list...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//CalendarGroups{calendargroup_id}/Calendars
  tags: Calendargroups, Calendargroup, , Calendars
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendargroupscalendargroup-idcalendars-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendargroupscalendargroup-idcalendars-get-openapi.md
- name: Microsoft Office 365 Add Calendar Groups Calendars
  x-api-slug: microsoft-office-365
  description: You can create a calendar by sending a POST request with a J...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//CalendarGroups{calendargroup_id}/Calendars
  tags: Calendargroups, Calendargroup, , Calendars
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendargroupscalendargroup-idcalendars-post-openapi.md
- name: Microsoft Office 365 Parameters Calendar Groups Calendars
  x-api-slug: microsoft-office-365
  description: Parameters calendargroups calendargroup  calendars
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//CalendarGroups{calendargroup_id}/Calendars
  tags: Calendargroups, Calendargroup, , Calendars
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendargroupscalendargroup-idcalendars-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendargroupscalendargroup-idcalendars-parameters-openapi.md
- name: Microsoft Office 365 Get Calendars Calendar
  x-api-slug: microsoft-office-365
  description: You can also retrieve information about a specific calendar ...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Calendars{calendar_id}
  tags: Calendars, Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendarscalendar-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendarscalendar-id-get-openapi.md
- name: Microsoft Office 365 Delete Calendars Calendar
  x-api-slug: microsoft-office-365
  description: Deleting a calendar is as simple as sending a DELETE request...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Calendars{calendar_id}
  tags: Calendars, Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendarscalendar-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendarscalendar-id-delete-openapi.md
- name: Microsoft Office 365 Patch Calendars Calendar
  x-api-slug: microsoft-office-365
  description: You can update a calendar by sending a PATCH request with a ...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Calendars{calendar_id}
  tags: Calendars, Calendar
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendarscalendar-id-patch-openapi.md
- name: Microsoft Office 365 Parameters Calendars Calendar
  x-api-slug: microsoft-office-365
  description: Parameters calendars calendar
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Calendars{calendar_id}
  tags: Calendars, Calendar
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendarscalendar-id-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendarscalendar-id-parameters-openapi.md
- name: Microsoft Office 365 Get Calendars Calendar Events
  x-api-slug: microsoft-office-365
  description: You can request all the events across all calendars (or a fi...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Calendars{calendar_id}/Events
  tags: Calendars, Calendar, , Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendarscalendar-idevents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendarscalendar-idevents-get-openapi.md
- name: Microsoft Office 365 Add Calendars Calendar Events
  x-api-slug: microsoft-office-365
  description: Post calendars calendar  events
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Calendars{calendar_id}/Events
  tags: Calendars, Calendar, , Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendarscalendar-idevents-post-openapi.md
- name: Microsoft Office 365 Parameters Calendars Calendar Events
  x-api-slug: microsoft-office-365
  description: Parameters calendars calendar  events
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Calendars{calendar_id}/Events
  tags: Calendars, Calendar, , Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendarscalendar-idevents-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/calendarscalendar-idevents-parameters-openapi.md
- name: Microsoft Office 365 Get Contact Folders Contact Folder
  x-api-slug: microsoft-office-365
  description: You can access the default contact folder by using the const...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//ContactFolders{contact_folder_id}
  tags: Contactfolders, Contact, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactfolderscontact-folder-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactfolderscontact-folder-id-get-openapi.md
- name: Microsoft Office 365 Parameters Contact Folders Contact Folder
  x-api-slug: microsoft-office-365
  description: Parameters contactfolders contact folder
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//ContactFolders{contact_folder_id}
  tags: Contactfolders, Contact, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactfolderscontact-folder-id-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactfolderscontact-folder-id-parameters-openapi.md
- name: Microsoft Office 365 Get Contact Folders Contact Folder Childfolders
  x-api-slug: microsoft-office-365
  description: All non-default contact folders are stored as children of th...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//ContactFolders{contact_folder_id}/ChildFolders
  tags: Contactfolders, Contact, Folder, , Childfolders
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactfolderscontact-folder-idchildfolders-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactfolderscontact-folder-idchildfolders-get-openapi.md
- name: Microsoft Office 365 Parameters Contact Folders Contact Folder Childfolders
  x-api-slug: microsoft-office-365
  description: Parameters contactfolders contact folder  childfolders
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//ContactFolders{contact_folder_id}/ChildFolders
  tags: Contactfolders, Contact, Folder, , Childfolders
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactfolderscontact-folder-idchildfolders-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactfolderscontact-folder-idchildfolders-parameters-openapi.md
- name: Microsoft Office 365 Get Contact Folders Contact Folder Contacts
  x-api-slug: microsoft-office-365
  description: You can request all contacts (or a filtered set by using the...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//ContactFolders{contact_folder_id}/Contacts
  tags: Contactfolders, Contact, Folder, , Contacts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactfolderscontact-folder-idcontacts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactfolderscontact-folder-idcontacts-get-openapi.md
- name: Microsoft Office 365 Add Contact Folders Contact Folder Contacts
  x-api-slug: microsoft-office-365
  description: You can create a contact by sending a POST request with a JS...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//ContactFolders{contact_folder_id}/Contacts
  tags: Contactfolders, Contact, Folder, , Contacts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactfolderscontact-folder-idcontacts-post-openapi.md
- name: Microsoft Office 365 Parameters Contact Folders Contact Folder Contacts
  x-api-slug: microsoft-office-365
  description: Parameters contactfolders contact folder  contacts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//ContactFolders{contact_folder_id}/Contacts
  tags: Contactfolders, Contact, Folder, , Contacts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactfolderscontact-folder-idcontacts-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactfolderscontact-folder-idcontacts-parameters-openapi.md
- name: Microsoft Office 365 Get Contacts Contact
  x-api-slug: microsoft-office-365
  description: You can retrieve information about a specific contact by usi...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Contacts{contact_id}
  tags: Contacts, Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactscontact-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactscontact-id-get-openapi.md
- name: Microsoft Office 365 Add Contacts Contact
  x-api-slug: microsoft-office-365
  description: You can create a contact by sending a POST request with a JS...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Contacts{contact_id}
  tags: Contacts, Contact
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactscontact-id-post-openapi.md
- name: Microsoft Office 365 Delete Contacts Contact
  x-api-slug: microsoft-office-365
  description: You can delete a contact by simply sending a DELETE request ...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Contacts{contact_id}
  tags: Contacts, Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactscontact-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactscontact-id-delete-openapi.md
- name: Microsoft Office 365 Patch Contacts Contact
  x-api-slug: microsoft-office-365
  description: To update a contact, send a PATCH request to the URL of the ...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Contacts{contact_id}
  tags: Contacts, Contact
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactscontact-id-patch-openapi.md
- name: Microsoft Office 365 Parameters Contacts Contact
  x-api-slug: microsoft-office-365
  description: Parameters contacts contact
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Contacts{contact_id}
  tags: Contacts, Contact
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactscontact-id-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactscontact-id-parameters-openapi.md
- name: Microsoft Office 365 Get Contacts Contact Attachments
  x-api-slug: microsoft-office-365
  description: To get attachments, send a GET request to the Attachments pr...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Contacts{contact_id}/Attachments
  tags: Contacts, Contact, , Attachments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactscontact-idattachments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactscontact-idattachments-get-openapi.md
- name: Microsoft Office 365 Add Contacts Contact Attachments
  x-api-slug: microsoft-office-365
  description: To add an attachment to an item, send a POST request to the ...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Contacts{contact_id}/Attachments
  tags: Contacts, Contact, , Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactscontact-idattachments-post-openapi.md
- name: Microsoft Office 365 Delete Contacts Contact Attachments
  x-api-slug: microsoft-office-365
  description: To delete an attachment, send a DELETE request to the URL of...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Contacts{contact_id}/Attachments
  tags: Contacts, Contact, , Attachments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactscontact-idattachments-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactscontact-idattachments-delete-openapi.md
- name: Microsoft Office 365 Parameters Contacts Contact Attachments
  x-api-slug: microsoft-office-365
  description: Parameters contacts contact  attachments
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Contacts{contact_id}/Attachments
  tags: Contacts, Contact, , Attachments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactscontact-idattachments-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/contactscontact-idattachments-parameters-openapi.md
- name: Microsoft Office 365 Get Events Event
  x-api-slug: microsoft-office-365
  description: You can also retrieve information about a specific event by ...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Events{event_id}
  tags: Events, Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/eventsevent-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/eventsevent-id-get-openapi.md
- name: Microsoft Office 365 Delete Events Event
  x-api-slug: microsoft-office-365
  description: Upon success, the appointment is moved to the user's Deleted...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Events{event_id}
  tags: Events, Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/eventsevent-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/eventsevent-id-delete-openapi.md
- name: Microsoft Office 365 Patch Events Event
  x-api-slug: microsoft-office-365
  description: To update an event, send a PATCH request to the URL of the e...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Events{event_id}
  tags: Events, Event
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/eventsevent-id-patch-openapi.md
- name: Microsoft Office 365 Parameters Events Event
  x-api-slug: microsoft-office-365
  description: Parameters events event
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Events{event_id}
  tags: Events, Event
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/eventsevent-id-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/eventsevent-id-parameters-openapi.md
- name: Microsoft Office 365 Add Events Event Accept
  x-api-slug: microsoft-office-365
  description: Post events event  accept
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Events{event_id}/Accept
  tags: Events, Event, , Accept
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/eventsevent-idaccept-post-openapi.md
- name: Microsoft Office 365 Parameters Events Event Accept
  x-api-slug: microsoft-office-365
  description: Parameters events event  accept
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Events{event_id}/Accept
  tags: Events, Event, , Accept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/eventsevent-idaccept-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/eventsevent-idaccept-parameters-openapi.md
- name: Microsoft Office 365 Add Events Event Decline
  x-api-slug: microsoft-office-365
  description: Post events event  decline
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Events{event_id}/Decline
  tags: Events, Event, , Decline
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/eventsevent-iddecline-post-openapi.md
- name: Microsoft Office 365 Parameters Events Event Decline
  x-api-slug: microsoft-office-365
  description: Parameters events event  decline
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Events{event_id}/Decline
  tags: Events, Event, , Decline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/eventsevent-iddecline-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/eventsevent-iddecline-parameters-openapi.md
- name: Microsoft Office 365 Add Events Event Tentatively Accept
  x-api-slug: microsoft-office-365
  description: Post events event  tentativelyaccept
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Events{event_id}/TentativelyAccept
  tags: Events, Event, , Tentativelyaccept
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/eventsevent-idtentativelyaccept-post-openapi.md
- name: Microsoft Office 365 Parameters Events Event Tentatively Accept
  x-api-slug: microsoft-office-365
  description: Parameters events event  tentativelyaccept
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Events{event_id}/TentativelyAccept
  tags: Events, Event, , Tentativelyaccept
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/eventsevent-idtentativelyaccept-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/eventsevent-idtentativelyaccept-parameters-openapi.md
- name: Microsoft Office 365 Get Firstsignin
  x-api-slug: microsoft-office-365
  description: Get firstsignin
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//FirstSignIn
  tags: Firstsignin
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/firstsignin-get-openapi.md
- name: Microsoft Office 365 Get Folders Folder
  x-api-slug: microsoft-office-365
  description: You can retrieve information about other folders by using th...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Folders{folder_id}
  tags: Folders, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/foldersfolder-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/foldersfolder-id-get-openapi.md
- name: Microsoft Office 365 Add Folders Folder
  x-api-slug: microsoft-office-365
  description: You can create a folder by sending a POST request with a JSO...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Folders{folder_id}
  tags: Folders, Folder
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/foldersfolder-id-post-openapi.md
- name: Microsoft Office 365 Delete Folders Folder
  x-api-slug: microsoft-office-365
  description: To delete a folder, send a DELETE request to the URL of the ...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Folders{folder_id}
  tags: Folders, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/foldersfolder-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/foldersfolder-id-delete-openapi.md
- name: Microsoft Office 365 Patch Folders Folder
  x-api-slug: microsoft-office-365
  description: You can update a folder by sending a PATCH request with a JS...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Folders{folder_id}
  tags: Folders, Folder
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/foldersfolder-id-patch-openapi.md
- name: Microsoft Office 365 Parameters Folders Folder
  x-api-slug: microsoft-office-365
  description: Parameters folders folder
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Folders{folder_id}
  tags: Folders, Folder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/foldersfolder-id-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/foldersfolder-id-parameters-openapi.md
- name: Microsoft Office 365 Get Folders Folder Messages
  x-api-slug: microsoft-office-365
  description: You can request all the emails and meeting requests in a fol...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Folders{folder_id}/Messages
  tags: Folders, Folder, , Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/foldersfolder-idmessages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/foldersfolder-idmessages-get-openapi.md
- name: Microsoft Office 365 Add Folders Folder Messages
  x-api-slug: microsoft-office-365
  description: You can create an email by sending a POST request with a JSO...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Folders{folder_id}/Messages
  tags: Folders, Folder, , Messages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/foldersfolder-idmessages-post-openapi.md
- name: Microsoft Office 365 Parameters Folders Folder Messages
  x-api-slug: microsoft-office-365
  description: Parameters folders folder  messages
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Folders{folder_id}/Messages
  tags: Folders, Folder, , Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/foldersfolder-idmessages-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/foldersfolder-idmessages-parameters-openapi.md
- name: Microsoft Office 365 Add Messages Event Send
  x-api-slug: microsoft-office-365
  description: You can send an existing email that has the IsDraft property...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{event_id}/Send
  tags: Messages, Event, , Send
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesevent-idsend-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesevent-idsend-post-openapi.md
- name: Microsoft Office 365 Parameters Messages Event Send
  x-api-slug: microsoft-office-365
  description: Parameters messages event  send
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{event_id}/Send
  tags: Messages, Event, , Send
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesevent-idsend-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesevent-idsend-parameters-openapi.md
- name: Microsoft Office 365 Get Messages Message
  x-api-slug: microsoft-office-365
  description: You can request information about a specific email or meetin...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}
  tags: Messages, Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-id-get-openapi.md
- name: Microsoft Office 365 Delete Messages Message
  x-api-slug: microsoft-office-365
  description: You can delete email by simply sending a DELETE request to t...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}
  tags: Messages, Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-id-delete-openapi.md
- name: Microsoft Office 365 Patch Messages Message
  x-api-slug: microsoft-office-365
  description: You can update an existing email by sending a PATCH request ...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}
  tags: Messages, Message
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-id-patch-openapi.md
- name: Microsoft Office 365 Parameters Messages Message
  x-api-slug: microsoft-office-365
  description: Parameters messages message
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}
  tags: Messages, Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-id-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-id-parameters-openapi.md
- name: Microsoft Office 365 Add Messages Message Copy
  x-api-slug: microsoft-office-365
  description: Post messages message  copy
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/Copy
  tags: Messages, Message, , Copy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idcopy-post-openapi.md
- name: Microsoft Office 365 Parameters Messages Message Copy
  x-api-slug: microsoft-office-365
  description: Parameters messages message  copy
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/Copy
  tags: Messages, Message, , Copy
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idcopy-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idcopy-parameters-openapi.md
- name: Microsoft Office 365 Add Messages Message Createforward
  x-api-slug: microsoft-office-365
  description: Post messages message  createforward
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/CreateForward
  tags: Messages, Message, , Createforward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idcreateforward-post-openapi.md
- name: Microsoft Office 365 Parameters Messages Message Createforward
  x-api-slug: microsoft-office-365
  description: Parameters messages message  createforward
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/CreateForward
  tags: Messages, Message, , Createforward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idcreateforward-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idcreateforward-parameters-openapi.md
- name: Microsoft Office 365 Add Messages Message Createreply
  x-api-slug: microsoft-office-365
  description: Post messages message  createreply
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/CreateReply
  tags: Messages, Message, , Createreply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idcreatereply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idcreatereply-post-openapi.md
- name: Microsoft Office 365 Parameters Messages Message Createreply
  x-api-slug: microsoft-office-365
  description: Parameters messages message  createreply
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/CreateReply
  tags: Messages, Message, , Createreply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idcreatereply-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idcreatereply-parameters-openapi.md
- name: Microsoft Office 365 Add Messages Message Create Reply All
  x-api-slug: microsoft-office-365
  description: Post messages message  createreplyall
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/CreateReplyAll
  tags: Messages, Message, , Createreplyall
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idcreatereplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idcreatereplyall-post-openapi.md
- name: Microsoft Office 365 Parameters Messages Message Create Reply All
  x-api-slug: microsoft-office-365
  description: Parameters messages message  createreplyall
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/CreateReplyAll
  tags: Messages, Message, , Createreplyall
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idcreatereplyall-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idcreatereplyall-parameters-openapi.md
- name: Microsoft Office 365 Add Messages Message Forward
  x-api-slug: microsoft-office-365
  description: You can forward an email by using the Forward action on the ...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/Forward
  tags: Messages, Message, , Forward
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idforward-post-openapi.md
- name: Microsoft Office 365 Parameters Messages Message Forward
  x-api-slug: microsoft-office-365
  description: Parameters messages message  forward
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/Forward
  tags: Messages, Message, , Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idforward-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idforward-parameters-openapi.md
- name: Microsoft Office 365 Add Messages Message Move
  x-api-slug: microsoft-office-365
  description: Post messages message  move
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/Move
  tags: Messages, Message, , Move
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idmove-post-openapi.md
- name: Microsoft Office 365 Parameters Messages Message Move
  x-api-slug: microsoft-office-365
  description: Parameters messages message  move
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/Move
  tags: Messages, Message, , Move
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idmove-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idmove-parameters-openapi.md
- name: Microsoft Office 365 Add Messages Message Reply
  x-api-slug: microsoft-office-365
  description: Post messages message  reply
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/Reply
  tags: Messages, Message, , Reply
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idreply-post-openapi.md
- name: Microsoft Office 365 Parameters Messages Message Reply
  x-api-slug: microsoft-office-365
  description: Parameters messages message  reply
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/Reply
  tags: Messages, Message, , Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idreply-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idreply-parameters-openapi.md
- name: Microsoft Office 365 Add Messages Message Replyall
  x-api-slug: microsoft-office-365
  description: Post messages message  replyall
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/ReplyAll
  tags: Messages, Message, , Replyall
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idreplyall-post-openapi.md
- name: Microsoft Office 365 Parameters Messages Message Replyall
  x-api-slug: microsoft-office-365
  description: Parameters messages message  replyall
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/ReplyAll
  tags: Messages, Message, , Replyall
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idreplyall-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/messagesmessage-idreplyall-parameters-openapi.md
- name: Microsoft Office 365 Get Services
  x-api-slug: microsoft-office-365
  description: Get services
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Services
  tags: Services
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/services-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/services-get-openapi.md
- name: Microsoft Office 365
  x-api-slug: microsoft-office-365
  description: Integrate Office 365 REST APIs powered by Microsoft Graph into your
    own app to connect to files, calendars, mail and more.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me
  tags: Microsoft Office 365
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/microsoft-office-365/master/_listings/microsoft-office-365/openapi.md
x-common:
- type: x-developer
  url: http://dev.office.com
- type: x-github
  url: https://github.com/OfficeDev
- type: x-twitter
  url: https://twitter.com/OfficeDev
- type: x-website
  url: http://office.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---