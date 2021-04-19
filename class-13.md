# HTML5 Storage

## What is HTML Web Storage?

With web storage, web applications can store data locally within the user's browser.

Before HTML5, application data had to be stored in cookies, included in every server request. Web storage is more 

secure, and large amounts of data can be stored locally, without affecting website performance.

Unlike cookies, the storage limit is far larger (at least 5MB) and information is never transferred to the server.

Web storage is per origin (per domain and protocol). All pages, from one origin, can store and access the same data.

interface Storage {

  getter any getItem(in DOMString key);
  
  setter creator void setItem(in DOMString key, in any data);
};



## USING HTML5 STORAGE

HTML5 Storage is based on named key/value pairs. 

You store data based on a named key, then you can retrieve that data with the same key. 

The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. 

However, the data is actually stored as a string. 

If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or 

parseFloat() to coerce your retrieved data into the expected JavaScript datatype.

## HTML web storage provides two objects for storing data on the client:

window.localStorage - stores data with no expiration date

window.sessionStorage - stores data for one session (data is lost when the browser tab is closed)
