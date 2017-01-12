# Docker container for COMS30106 assignment #
Container with [COMS30106 assignment](https://github.com/COMS30106/assignment).

## Usage ##
```
docker run -p 8000:8000 -v /local/path/to/my/solution/assignment1_12345.pl:/home/jovyan/assignment/assignment1_12345.pl -it coms30106/assignment
```
Where `/local/path/to/my/solution/assignment1_12345.pl` is path to a local file with your solution, and `/home/jovyan/assignment/assignment1_12345.pl`is simulated file on the docker machine. In the latter you should only change the file name i.e. `assignment1_12345.pl`.  
Finally, point your browser to [http://localhost:8000](http://localhost:8000) to access the assignment environment.

## Build ##
```
docker build -t coms30106/assignment .
```
