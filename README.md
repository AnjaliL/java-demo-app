### Instructions to use
#### updated the file directly checking fetch
- Clone the repo

    ```git clone https://github.com/AnjaliL/java-demo-app```
- Change directory

    ```cd java-demo-app```
- To build image

    ```docker build -t demoapp -f Dockerfile .```
- Create Container
    
    ```docker run -d -p 8091:8080 demoapp```
