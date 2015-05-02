# Tag List

This is a draft project for pulling tags from Flickr. 

Workflow
---

- Loop through list of photo_ids
- Ajax call to get photo info via API
- parse words from <title> and <description>
- build arrays of words, clean
- count word frequencies 
- clear <table> tag
- refresh with word frequencies table 

Issues
---

- Tag list on Flickr is not robust, need to rely on title and descriptions

