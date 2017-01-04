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
move *.pdf website
move *.epub website
cd website
http-server
```

Then open chrome and type `http://localhost:8080`


