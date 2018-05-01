# Bots
Bots that we are using in our organization.

### 1. Unfurl

Originally made by **PROBOT**. We added some new features of our own.

**Added functionality :**

1.) User have to create a ```.github/settings.yml``` file where they will set the maximum URL's to unfurl like this :

```
maxUrl : 3 // can set to anything they want
```
If not set then default of 10 links will be unfurled 

2.) Now only `maxUrl` number of links will be unfurled by bot.

3.) Added unfurl feature when issue or pull-request is edited.

4.) If they edit the comment and do not provide any link then stopped sending attachments.

5.) Avoid unfurling of same URL's

- [Deployed on glitch](https://glitch.com/edit/#!/ember-attic)

- [Click to Install on repos](https://github.com/apps/unfurl)
