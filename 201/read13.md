### THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS

- native applications usually provieds an abstraction layer for storing and retriving data , and can be stores in registry 
- web application , didnt had the same as native application until cookies were created.
- there are 3 dealbreking downsiders; they might slow down your web application by transfering data over and over again 
 the send unencrypted data over the internet , and they have a limit 4kb of data.
- `user data` that was cerated by Microsoft allwowed web pagese o store up to 64KB of  data per domain .
- `Local shared Object`s that was created bt Adobe allows flsh obj to store up to 100 KB of data per domain.
- `Gears`was created by Google it aimed to provide addittional capabilities in browsers.

## HTML5 storge
- also referd as web storge, local storge ,DOM storge.
- its a way for web pages to store named key/value pairs within the client web browser.
- we can access HTML5 storge through JavaScript code  by the localStorge Object on the globe window object.but we have to check if the browser supports it first.
- we store data based on named key then we retirive that data with tthe same key,this is used for all types of data supported by JavaScript
- if we want to retrive other than string data we want we can use functions like `parseInt() or parseFloat()`.
- we can treat the localstorge as an array.
## tracking Changes to the HTML5 Storge Area:
- to track when the storge area changes we can trap the storge event that is fired on the window object whenever `setItem()removeItem(), or clear() ` is called .
- the storge event is supported everywhere the LocalStroge objct is supporeted .

![storgeEvent Proparites](201/read1212.jpg)


limitaions in current browsers 
- 5 megabytes : which is the storge space each origin get by defult.
- `“QUOTA_EXCEEDED_ERR”` its the exception that will be thrown if we exceed the storge quota of 5 megabytes.

##BEYOND NAMED KEY-VALUE PAIRS: COMPETING VISIONS
- A new API has been standardized and implemented on all makor browsers  and platforms and devices.
- eb SQL Database allow us to things from JavaScript.
- Indexed Database API has a *objectstore* that shares many concepts with SQL database.
- there are databasesa and records ,where each record has a set of fields each of which has a spacific data taype.
- the object store has no sturcutures query language , we use methods and provided by the object store to open a cursor on the data base.



