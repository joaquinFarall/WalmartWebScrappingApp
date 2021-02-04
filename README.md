# Walmart WebScrapping App
## A products management system where you can create users to login the app with all the authentifications and with change password and forgot password functionalities. Where you can add products to the DB by webscrapping the product's name, price, stock from walmart.com website and saving it with an unique sku. Also you can edit the product's information or delete them. It contains a dashboard that displays how many products there are in the DB, how many are updated or not updated, how many are in stock, not in stock or back in stock and with pages to display tables with all the products. Last but not least, an update functionality that updates every single product with the real data from walmart.com by automathically webscrapping the website   
### used Node, Express, ejs, mongoose, puppeteer, cheerio, passport, connect-flash and other npm packages

#### To use: 
> $ npm init 
> $ npm i express passport cheerio ejs dotenv puppeteer node-mailer method-override path mongoose express-session body-parser connect-flash --save
