1. Open the Node.js command prompt
2. enter the following lines of code in the prompt

```
cd Desktop\Gregs Docs\gregt-mobile
dir
```

Find the name of the directory containing the book you want to build.

```
cd {DIRECTORY_NAME}
gitbook build . website
gitbook pdf .
gitbook epub .
copy book.student.json book.json
gitbook build . website\student
gitbook pdf .
gitbook epub .
move *.pdf website\student
move *.epub website\student
copy book.master.json book.json
cd website
http-server
```

Then open chrome and type `http://localhost:8080`


