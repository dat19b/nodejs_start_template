# Nodejs & Docker starter files

## Commandline (terminal (mac), Powershell (windows))
1. Clone this repository
2. ```cd nodejs_start_template ```
3. Build the docker images by running:``` docker build -t clbo_node . ```
4. Create and Run a Container based on this image: ``` docker run -it --rm -p 8080:8080 -v ${PWD}:/app clbo_node bash ```
5. In the terminal ``` cd app ```
6. In the terminal ``` node server/server.js ```
7. http://loacalhost:8080

## Intellij
1. Clone this repository 
2. open in intellij
3. press the green run button. 
4. go to http://localhost:8080 (you should see the index.html page from the public folder)

If this for some reason does not work notify your teacher. 
