---
swagger: "2.0"
x-collection-name: Microsoft Office 365
x-complete: 0
info:
  title: Microsoft Office 365 Add Calendar Groups
  description: You can create a calendar group by sending a POST request wi...
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