# nodejs-mssql

The tutorial I used to create this was mainly this: 
https://vmokshagroup.com/blog/building-restful-apis-using-node-js-express-js-and-ms-sql-server/

and some help from this:
https://vooban.com/en/tips-articles-geek-stuff/how-to-quickly-create-a-simple-rest-api-for-sql-server-database/

'Tedious' is used in the package-lock.json folder to connect MS SQL.

server.js has the database config information you'll need to hook to your local DB. The only thing you will need to do is either create a new user locally with the username and password in the file, or change those to one you want to use.

