# API Development Environment – LMS Assessment

## Overview
This repository contains the deliverables for the Topic 1 LMS Assessment: **Setting Up Your API Development Environment**.

## Tools Used
- Postman
- n8n Cloud
- JSONPlaceholder public REST API

## API Endpoint
`https://jsonplaceholder.typicode.com/users`

## Assessment Work Completed
- Created a Postman personal workspace named **API Development Environment**.
- Executed a **GET** request against the JSONPlaceholder Users API.
- Verified the successful **200 OK** response in Postman.
- Inspected the returned JSON response.
- Configured an n8n workflow named **API Development Environment - HTTP GET**.
- Connected a Manual Trigger to an **HTTP Request** node.
- Configured the HTTP Request node with the GET method and the public API endpoint.
- Executed the workflow successfully and inspected the returned JSON data.
- Exported the n8n workflow as JSON for submission.

## Workflow Structure
```text
When clicking "Execute workflow"
              ↓
        HTTP Request
              ↓
       JSON Response
```

## Demo Video
[Loom Demo](https://www.loom.com/share/c965192cb8664a47b75f484d7aa2a137)

## Deliverables
- `README.md` – project and assessment summary
- `API Development Environment - HTTP GET.json` – exported n8n workflow

## Notes
The workflow is intended as a basic API development demonstration showing client-server communication through an HTTP GET request, successful execution, and JSON response inspection.
