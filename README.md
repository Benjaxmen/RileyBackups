# RileyBackups
The repository for the demo of an App to upload data   
To succesfully execute the server you have to run the following command: sudo uvicorn main:app --env-file=.env --host 0.0.0.0 --port=8000   
To enter the server you have to go into http://*assigned IP*:8000/docs and try the post in there   
Where assigned IP is the public IP of your virtual machine    
To retrieve a file you have to go into http://*assigned IP*:8000/storage/blob/file/*container*/*filename.extension*   
Where the blob container name goes in *container* and the filename goes in *filename.extension*   
