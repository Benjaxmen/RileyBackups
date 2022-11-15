# RileyBackups
The repository for the demo of an App to upload data   
To succesfully execute the server you have to run the following command: sudo uvicorn main.app --env-file=.env --host 0.0.0.0 --port=8000   
To enter the server you have to go into http://20.127.89.69:8000/docs and try the post in there   
To retrieve a file you have to go into http://20.127.89.69:8000/storage/blob/file/*container*/*filename.extension*   
Where the blob container name goes in *container* and the filename goes in *filename.extension*   
