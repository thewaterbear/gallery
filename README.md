
##### work in progress, don't use yet :)

#### Gallery is a simple backendless portfolio site

Gallery uses angular + isotope.js to create a clean, simple, sortable display of images.

### Getting Started
``` 
$ git clone https://github.com/thewaterbear/gallery.git
```

- Replace images with your own in the /images folder
- Edit db.json to your desire

#### Local Preview
Since gallery is only a frontend, you can preview it locally using any webserver like WAMP, MAMP, XAMMP or any node servers.
Lets use http-server 
(Assuming you have node and npm installed)
 ```
 $ npm install http-server -g
 ```
 in gallery directory
 ``` 
 $ http-server 
 ```

#### Delpoy
if you don't have surge installed..
``` 
$ npm install --global surge
```
In your project directory, just run…
```
$ surge
```

Alternativley, you can place the files themselves on any webserver via FTP or any other means.

Thats it!

#### To Do

- Add a adminUI that makes it easy to drag+drop images into the gallery and updated db.json



#### Reasons for building this
...

#### Drawbacks of frontend only
...