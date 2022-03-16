# Notes from Read: 13 Local Storage
[Home](README.md)

## The Past, Present & Future of Local Storage for Web Applications
Ref: http://diveinto.html5doctor.com/storage.html

Introducing HTML5 Storage <br>
- you need to check for HTML Storage <br>
- data type can be anything that is supported by JS but will be stored as a string <br>
- you will need to use parseInt and parseFloat to find anything not a string <br>
- calling setItem() with a named key that already exists will overwrite the original <br>
- you can remove date with the deleter void removeItem() and void clear() <br>
- to get the name of each key you can use readonly attribute unsigned long length; getter DOMString key <br>

Tracking changes to the HTML5 Storage Area <br>
-  you can add eventlisteners, handlestorage, and attach event
- The handle_storage callback function will be called with a StorageEvent object, except in Internet Explorer where the event object is stored in window.event. <br>
- storage events are not cancelable, handle_storage callback fucktion will tell you whats happening though <br>

limitations in current browsers <br>
- 5 MB is how much storage is default across all browsers <br>
- "QUOTA_EXCEEDED_ERR" is the exception y ou will be passed if you go over that limit <br>

HTML5 Storage in Action
- brower can save data from the user by affecting the localStorage <br>
- because everything is stored as a string you will need to coerce it when you retrieve it <br>