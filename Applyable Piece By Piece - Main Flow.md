### About
This component was the last component for ApplyAble, and perhaps the most important one, because it was responsible for sending and receiving emails, processing the jobs in the google sheet and covering the overall part of the application

### Tech Stack
- `n8n`
- `docker`
- `AWS`

### Why `n8n`
Had a huge time crunch... n8n came with integrations out of the box... But so did zapier. Why n8n? Because fair-code, deployed with docker... I already had an AWS setup... Very low cost compared to zapier... Better workflow (opinionated)...

### Process

**Google Cloud API**
- Make project
- Set credentials (for developers)
- Enable `google sheets API` and `gmail API`

**n8n Setup**
- Setup with docker
- `dev` and `start` scripts
- Workflow
- Deployment to AWS

### Common problems and solutions

**Workflow and usage for `n8n`**
New technology... Not so well known... Had to use my own methods because things on web are unnecessarily complex... (https://github.com/esxr/n8n-docker-setup)

**Importing external libraries into `n8n`**



