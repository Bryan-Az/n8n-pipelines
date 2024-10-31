# n8n's json flows

n8n is able to save any automation flow as a json and is able to load it in either the cloud, docker, or command line node.js n8n GUI. The first 2 flows (discord chat and file edit flows) were tested using the cloud n8n hosting service using the free trial - however, this caused the flow to stop executing after the max num of exections were reached. I was able to continue building and testing the flows using the locally hosted version of n8n and this was facilitated by using the json flow templates - although the credentials needed to be re-added in the GUI as these cannot be saved in the flows.

## Flow Image Demos

1. A ChatGPT-4o Chatbot pipeline that is available as a bot in Discord.

![flow1](/json_pipelines/images/chatgpt-4o-discord-flow.png)

2. A Questionnaire and Follow-Back (human in the loop) pipeline.

![flow2](/json_pipelines/images/feedback_flow.png)

3. A File-Edit notification pipeline using event triggers in Google Drive.

![flow3](/json_pipelines/images/google_flow.png)
