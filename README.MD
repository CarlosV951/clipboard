# Clipboard
The project is a web application that allows the creation of a server, both locally and in the cloud, using a Node.js backend and a React frontend. The application is designed to manage and store links and texts in a simple way, with the possibility of adding more tools in the future. Users can perform quick searches among the stored bookmarks, improving accessibility to information. In addition, the backend structure is prepared with endpoints that allow its implementation in any programming language, offering flexibility for future extensions or adaptations of the system.

# Endpoints

## Endpoint 1 (Save marker)
Guarda la informacion del marcador que se reciba ya sea link o texto.
### Input
```json
{
  "text": "text",
  "type": "link"
}
```
### Response
```json
{
  "response": "Description"
}
```
