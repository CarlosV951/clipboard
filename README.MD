# Clipboard
The project is a web application that allows the creation of a server, both locally and in the cloud, using a Node.js backend and a React frontend. The application is designed to manage and store links and texts in a simple way, with the possibility of adding more tools in the future. Users can perform quick searches among the stored bookmarks, improving accessibility to information. In addition, the backend structure is prepared with endpoints that allow its implementation in any programming language, offering flexibility for future extensions or adaptations of the system.

# Tecnology
## Node JS 16+
## MYSQL 8.0+
## React 

# Endpoints

## Endpoint Create marker (/api/mark) - POST
Saves the bookmark information that is received, whether it is a link or text.
### Input
```json
{
  "text": "text",
  "type": "link"
}
```
### Output
```json
{
  "response": "Description"
}
```

## Enpoint Read markers (/api/mark) - GET
Returns the bookmarks stored in the database.
### Input
```json
{
}
```
### Output
```json
{
[
  {
    "idMark": 0,
    "type": "type1",
    "text": "text
  },
  {
    "idMark": 1,
    "type": "type2",
    "text": "text
  }
]
}
```
