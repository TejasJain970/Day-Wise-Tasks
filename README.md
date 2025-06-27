# Internship Day Wise Progress
DAY-1

About CVAT(Computer Vision Annotation Tool)
1. Free, open source, web based platform to annotate images and videos for computer vision
2. Use of bounding boxes and polygons etc.

DAY-2

Local Host CVAT
1. Locally hosted CVAT using Docker
2. Used stock image to practice and implement annotations

# Socket Programming
DAY-3

tcpserver.py
1. Created a Server file and then created a socket
2. Binded the socket with specific IP and Port
3. Encoded a message to byte type which will be shared when successfully connected to client


client.py
1. Created a Client file and a new socket
2. Connection is established on the defined port
3. Data is received and decoded

DAY-4

headerserver.py
1. Added a header of lenght 10 through which a message of maximum 1 billion characters can be shared/received
2. Used left alignment for header string interpretation


headerclient.py
1. Data is received and decoded with a 16 bytes buffer
2. Message is decoded until all characters and then printed without the header


pickleserver.py
1. Used pickle(dumps) to serialize data from object to binary format
2. In this case dictionary was used


pickleclient.py
1. Used pickle(loads) to deserialize data to object from binary format
2. Received the dictionary in object form
