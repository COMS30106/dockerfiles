# Docker container for COMS30106 prolog_intro #
Container with [COMS30106 prolog_intro](https://github.com/COMS30106/prolog_intro).

## Usage ##
```
docker run -p 3050:3050 -it coms30106/prolog_intro
```
Finally, point your browser to [http://localhost:3050](http://localhost:3050) to access the SWISH environment.  
Graphviz intro is then located in [http://localhost:3050/example/graphviz_intro.swinb](http://localhost:3050/example/graphviz_intro.swinb) and Prolog intro in [http://localhost:3050/example/self_study.swinb](http://localhost:3050/example/self_study.swinb).

## Build ##
```
docker build -t coms30106/prolog_intro .
```
