# assignmentmern
It's important to note that creating a full-fledged Google Docs clone can be a complex and time-consuming task, especially if you want to replicate all of its features. Additionally, you'll need to consider legal and copyright implications if you're planning to release the application publicly.


start with npm run dev in #Frontend
start with npm run dev in #Backend

The following table lists the available API routes and their descriptions:

| Route | Method | Description |
|-------|-------------|----------|
| auth/signup/ | `POST` | Register user's data in Database |
| auth/signin/ | `POST` | By checking user's credentials allow them to log-in in the web-applicattion |
| profile/ | `PATCH` |	Update logged-in user's profile |
| docs/ | `GET` |	Get all public docs |
| docs/user | `GET` |	Get all docs for the logged-in user |
| docs/ | `POST` | Post / Create document |
| docs/:docId | `PATCH` | Update specific doc's details and allowed only for the author |
| docs/:docId | `DELETE` | Delete specific doc and allowed only for the author |

Thank you 💙
