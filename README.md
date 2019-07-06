# Yensesa

Yensesa wallet is your decentralised blockchain wallet where you can buy/sell digital assets, earn interest on your assets and access loans.
## Installation
```bash
cd frontend
npm install
```
## Run
After install
```bash
npm start
```

## Source Tree
```
| .env 									// Set Environment
| .gitignore 							// Ignore File
| package.json 							// Define Packet npm
|   
+---public								//Public folder
| index.html								// Main Index.html
| yensesa-favicon.png						// Icon of web
|       
+---src									// Main Source Folder
    |   index.js
    |   
    +---assets							// General Resource: Fonts, Js, Images
    |   +---fonts						
    |   |       Tahoma.ttf   
    |   +---images
    |   |       icon-add.svg
    |   |       icon-ask.svg
    |   |       icon-dropdown.svg
    |   |       icon-flag-ghana.svg
    |   |       icon-flag-usa.svg
    |   |       icon-right-arrow-w.svg
    |   |       yensesa-favicon.png
    |   |       yensesa-logo.svg
    |	|		....
    |   |       
    |   \---js
    |           reset.css
    |           
    +---components						// All Component(Add more component in there)
    |   |   index.js
    |   |   
    |   \---App							// App Component
    |           App.css
    |           App.jsx
    |           index.js
    | 
    ...
    \---services						// Api services
            ApiService.js
            index.js
 ```
