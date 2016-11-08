
1. cd final  
2. `mvn clean appengine:devserver`

<!---
1. What dependencies does it have (where are they expressed) and how do I install them?
1. Can I see the project working before I change anything?

How do I run the project's automated tests?

* Unit Tests

* Integration Tests
 -->

## Deploying

### How to deploy

1. Create a project in [Google Cloud Console](https://cloud.google.com/console)
1. edit ...**/webapp/WEB-INFappengine.web.xml** and change **your-app-id**
1. `mvn clean appengine:update`
reference https://cloud.google.com/appengine/docs/java/gettingstarted/creating-guestbook
