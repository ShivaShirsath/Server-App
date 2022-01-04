# Live-Server-App
+ Get IP for to test website on connected device on same WiFi
  
  use below command on [ Android ( [TermUX](https://play.google.com/store/apps/details?id=com.termux) / [Pydroid 3](https://play.google.com/store/apps/details?id=ru.iiec.pydroid3) Terminal ) , Ubuntu ( Terminal ) ]
  ```css
  ip addr
  # Or
  python -m http.server 8000 --bind 127.0.0.1 --directory /path
  ```
+ Use other than localhost ( remember port number )
  ```bash
  http://ip:port 
  # Or
  termux-open https://127.0.0.1:8000
  ```
+ [⇩ apk](https://www.mediafire.com/file/aoeub2ilvpdx5vs/Live_Server.apk) Live Server
+ [⇩ apk](https://www.mediafire.com/file/7jl1m71a3fg44ve/Python+Server.apk) Python Server
