## **Local environment:** 
- Docker - server virtualization.  
- Visual Studio code CE - IDE. 
## **Staging site:** 
AWS 
## **Production site:** 
DreamHost 
## **Project management:** 
- Trello – management tool for idea and work focus 
- Slack – commutation text for major announcements 
- Discord – meeting, live work groups 
## **Version control:** 
- Git – version control architecture 
- GitHub – code publishing and sharing between team 
## **Testing and automation:** 
- BrowserSync – live testing 
- Glup – automation  

## **The Process:**
Cloning the repo from GitHub on to your local environment. Start Docker then in the CLI (GitBash or terminal) in your folder where you downloaded the repo of the theme run the docker-compose.yml \
After Docker containers have spun up, open VS code and in the terminal enter  

```
npm run dev      
```
\
this will start BrowserSync and you can start making changes to the theme. Making commits to Git on your branch.
When you need commit to GitHub and make a pull request to reviewed by other team member(s) after this has been approved and merged. This will integrate the changes into the theme.
From there you can use the 

```
npm run bundle 
```
\
to make a zip file to upload to the staging site for testing and if no problems then take the file to the production site 
and deploy the theme on the production site.

