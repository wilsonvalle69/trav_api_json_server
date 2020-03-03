<h1>Fake API JSON-server<h1>

Online Test API <br>
jsonplaceholder.typecode.com

<h2>Commands</h2>
npm install -g json-server  <br>
npm init    <br>
npm install --save json-server <br>
npm install -g jsdoc    <br>
<br>

Start JSON Server <br>
```
npm run json:server
json-server --watch db.json --port 3004    # replace by script json:server
```
<br>

Links

http://localhost:3004

get the whole database  <br>
http://localhost:3004/db

get whole list of users <br>
http://localhost:3004/users

get single User <br>
http://localhost:3004/users/1

get users from specific company <br>
http://localhost:3004/companies/1/users

filter companies by name    <br>
http://localhost:3004/companies?name=Apple&name=Hexagon

pagination and limit    <br>
http://localhost:3004/users?_page=2&_limit=2

sorting <br>
http://localhost:3004/companies?_sort=name&_order=asc

users age range <br>
http://localhost:3004/users?age_gte=30
http://localhost:3004/users?age_gte=30&age_lte=40

full text search<br>
http://localhost:3004/users?q=John


Adding data with POST from Postman   <br>
url: localhost:3004/equipment
headers: Content-Type: application/json
body sample:
{
	"id": "4",
    "code": "HT-150",
    "equipmentTypeId": "2"
}




