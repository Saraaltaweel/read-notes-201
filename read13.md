## THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS

in the past Cookies were invented early in the web’s history and we can use it to storge small amount od data by it has 3 disatvantage:
1. Cookies are included with every HTTP request becouse it lead to slowing down the web application by repeat to transform the data 

2. Cookies are included with every HTTP request that lead to send data unencrypted over the internet

3. Cookies are limited to about 4 KB of data thats enough to alow down your application 

### HTML5 Storage
*it’s a way for web pages to store named value pairs locally, within the client web browser. Like cookies*
![](img/html.PNG)

to check HTML5 storage write this:
`function supports_html5_storage() {`
  `try {`
   ` return 'localStorage' in window &&` `window['localStorage'] !== null;`
  `} catch (e) {`
    `return false;`
  `}`
`}`
*SQL. In 2007, Google launched Gears, an open source cross-browser plugin which included an embedded database based on SQLite. This early prototype later influenced the creation of the Web SQL Database specification. Web SQL Database (formerly known as “WebDB”) provides a thin wrapper around a SQL database*
![](img/sql.PNG)