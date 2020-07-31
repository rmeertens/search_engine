docker build -t searchengine . && docker run -it -p 8888:8888 -v $(pwd):/workspace  searchengine

