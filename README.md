# Template for CodeRefinery workshop webpages

This repository is a template to set up webpages for CodeRefinery workshops.

To use it, follow these instructions:
- Click the green "Use this template" button.
- Select owner of the new repository and repository name. The name should be
  "year-month-date-place", e.g. "2019-10-16-stockholm".
- Click "Create repository from template"
- You will now be redirected to the new repository.

Adjust these files:
- `title.md`
- `left-column.md`
- `right-column.md`

### Schedule planning

Mini-hackathon roles and self-assignment:

- **Host:** Manage zoom meeting, breakout rooms, timekeeping and breaks,
   zoom chat, general attendee communication.
   - Name1
 - **Hackmd:** watches hackmd, answers questions, organizes it, brings questions up in main lecture.
   - Samantha
   - Name3
 - **Mentors:** get paired with a few participants on day 1 and answer questions by email in the period until day 2.
   Also work as helpers in breakout rooms on day 1.
   - Johan
   - Qiang Li, ENCCS
   - Mark Abraham, ENCCS
   - Roberto Di Remigio, ENCCS
 - **Instructors:** Teach the lesson on day 1
   - NameN+1
   - NameN+2
   - NameN+3


### Changing the status of the registration button

Registration is not yet open:
```html
<a class="btn btn-info disabled" href="#" data-mode="1" target="_blank">Registration will open soon</a>
```

Registration is open (adjust the `href`):
```html
<a class="btn btn-success" href="#" data-mode="1" target="_blank">Register here</a>
```

Registration is closed:
```html
<a class="btn btn-danger disabled" href="#" data-mode="1" target="_blank">Registration is closed</a>
```
