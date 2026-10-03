<!-- SHOWCASE_START --><div align="center">[![Typing](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=900&lines=api%20development%20environment;AI%20%7C%20Automation%20%7C%20Engineering;Explore%20the%20project%20%F0%9F%9A%80)](https://github.com/shaikshahid777/api-development-environment)<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:161B22,100:58A6FF&height=110&section=header&text=api-development-environment&fontSize=26&fontColor=FFFFFF&animation=twinkling&fontAlignY=65" width="100%" alt="Animated project banner"/>

[![Repository](https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shaikshahid777/api-development-environment) [![Issues](https://img.shields.io/badge/Report-Issue-red?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/api-development-environment/issues/new) [![Stars](https://img.shields.io/github/stars/shaikshahid777/api-development-environment?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/api-development-environment/stargazers) [![Fork](https://img.shields.io/github/forks/shaikshahid777/api-development-environment?style=for-the-badge&logo=github)](https://github.com/shaikshahid777/api-development-environment/fork) [![Profile](https://img.shields.io/badge/Profile-Visit-0A66C2?style=for-the-badge&logo=github)](https://github.com/shaikshahid777)</div>

> ✨ **Project Showcase Mode:** animated banner • interactive navigation • live repository actions

[🚀 Repository](https://github.com/shaikshahid777/api-development-environment) · [🐞 Report Issue](https://github.com/shaikshahid777/api-development-environment/issues/new) · [⭐ Star](https://github.com/shaikshahid777/api-development-environment/stargazers) · [🔱 Fork](https://github.com/shaikshahid777/api-development-environment/fork) · [👤 Profile](https://github.com/shaikshahid777)

<!-- SHOWCASE_END -->

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
