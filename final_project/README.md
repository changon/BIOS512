```bash
docker build -t course_project .
```

(builds image from Dockerfile in cwd into image called course_project).


```bash
docker run -it --rm -w $PWD -v $PWD:$PWD -p 9999:9999 course_project jupyter lab --port 9999
```

To run this.

Usually for another one, docker run pulls image (from repo) and then runs it.


Cool Tricks:
ctrl r to reverse search commands of a string in terminal
