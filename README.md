# Live-Server-App
+ Get IP for to test website on connected device on same WiFi
   
use on

  Android => [TermUX](https://play.google.com/store/apps/details?id=com.termux) / [Pydroid 3 Terminal](https://play.google.com/store/apps/details?id=ru.iiec.pydroid3)
  
  Ubuntu => any Terminal
***
#### Command
```css
ip addr
```
**_Or_**
```css
ip=127.0.0.1
port=8000
path=$HOME/project
```
```js
python -m http.server $port --bind $ip --directory $path
```
***
#### Use
```css
http://ip:port
```
**_Or_**
```css
termux-open https://ip:port
```
***
+ [⇩ apk](https://www.mediafire.com/file/aoeub2ilvpdx5vs/Live_Server.apk) Live Server
+ [⇩ apk](https://www.mediafire.com/file/7jl1m71a3fg44ve/Python+Server.apk) Python Server
***
#### Auto reload
```javascript
document.addEventListener('visibilitychange', e =>{
  if (document.visibilityState === 'visible') {
    document.location.reload(true);
  }
});
```
