1.cd final

## Deploying

### How to deploy

2. Create a project in [Google Cloud Console](https://cloud.google.com/console)
3. edit ...**/webapp/WEB-INFappengine.web.xml** and change **your-app-id**
4. Go to final dir and do  `mvn clean appengine:update`
reference https://cloud.google.com/appengine/docs/java/gettingstarted/creating-guestbook
