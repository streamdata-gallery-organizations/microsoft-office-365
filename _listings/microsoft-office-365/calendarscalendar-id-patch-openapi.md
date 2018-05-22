---
swagger: "2.0"
x-collection-name: Microsoft Office 365
x-complete: 0
info:
  title: Microsoft Office 365 Patch Calendars Calendar
  description: You can update a calendar by sending a PATCH request with a ...
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