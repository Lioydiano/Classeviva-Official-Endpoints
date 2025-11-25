# Classeviva Official Endpoints
This repository provides the list of official Endpoints for Classeviva

***

## Libraries
* [`Classeviva.py`](https://github.com/Lioydiano/Classeviva)

## How to contribute
If you want to contribute, please open a pull request using template file
***

## Endpoints
_API Url: <code>https://web.spaggiari.eu/rest/</code>_

## Request Header
- User-Agent: <code>CVVS/std/4.1.7 Android/10</code>
- Z-Dev-ApiKey: <code>Tg1NWEwNGIgIC0K</code>
- ContentsDiary-Type: <code>application/json</code>

_Warning: without these headers, the request will fail._

### Authentication
- **[<code>POST</code> v1/auth/login](Authentication/login.md)**
- **[<code>GET</code> v1/auth/avatar](Authentication/avatar.md)**
- **[<code>GET</code> v1/auth/status](Authentication/status.md)**
- **[<code>GET</code> v1/auth/ticket](Authentication/ticket.md)**

### User
##### Absence
- **[<code>GET</code> v1/students/_{studentId}_/absences/details](Absences/absences.md)**
- **[<code>GET</code> v1/students/_{studentId}_/absences/details/_{begin}_](Absences/from.md)**
- **[<code>GET</code> v1/students/_{studentId}_/absences/details/_{begin}_/_{end}_](Absences/from_to.md)**
##### Agenda
- **[<code>GET</code> v1/students/_{studentId}_/agenda/all/_{begin}_/_{end}_](Agenda/from_to.md)**
- **[<code>GET</code> v1/students/_{studentId}_/agenda/_{eventCode}_/_{begin}_/_{end}_]()**
##### Didactics
- **[<code>GET</code> v1/students/_{studentId}_/didactics](Didactics/didactics.md)**
- **[<code>GET</code> v1/students/_{studentId}_/didactics/item/_{contentId}_]()**
##### Notice Board
- **[<code>GET</code> v1/students/_{studentId}_/noticeboard](Noticeboard/noticeboard.md)**
- **[<code>POST</code> v1/students/_{studentId}_/noticeboard/read/_{eventCode}_/_{pubId}_/101]()**
- **[<code>GET</code> v1/students/_{studentId}_/noticeboard/attach/_{eventCode}_/_{pubId}_/101]()**
##### Schoolbooks
- **[<code>GET</code> v1/students/_{studentId}_/schoolbooks](Schoolbooks/schoolbooks.md)**
##### Calendar
- **[<code>GET</code> v1/students/_{studentId}_/calendar/all](Calendar/calendar.md)** 🤔🤔🤔
##### Card
- **[<code>GET</code> v1/students/_{studentId}_/card](Card/card.md)**
- **[<code>GET</code> v1/students/_{studentId}_/cards](Card/cards.md)**
##### Grades
- **[<code>GET</code> v1/students/_{studentId}_/grades](Grades/grades.md)**
##### Lessons
- **[<code>GET</code> v1/students/_{studentId}_/lessons/today](Lessons/lessons.md)**
- **[<code>GET</code> v1/students/_{studentId}_/lessons/_{day}_](Lessons/lessons.md)**
- **[<code>GET</code> v1/students/_{studentId}_/lessons/_{start}_/_{end}_](Lessons/lessons.md)**
##### Notes
- **[<code>GET</code> v1/students/_{studentId}_/notes/all](Notes/all.md)**
- **[<code>POST</code> v1/students/_{studentId}_/notes/_{type}_/read/_{note}_](Notes/read.md)**
##### Periods
- **[<code>GET</code> v1/students/_{studentId}_/periods](Periods/periods.md)**
##### Subjects
- **[<code>GET</code> v1/students/_{studentId}_/subjects](Subjects/subjects.md)**
##### Documents
- **[<code>POST</code> v1/students/_{studentId}_/documents](Documents/documents.md)**
- **[<code>POST</code> v1/students/_{studentId}_/documents/check/_{hash}_](Documents/check%20document.md)**
- **[<code>POST</code> v1/students/_{studentId}_/documents/read/_{hash}_](Documents/read%20document.md)**
### QR-Code
##### Upload
- **[<code>POST</code> tools/app/default/app_qrcode_token.php?a=aUPLIMG]()**
