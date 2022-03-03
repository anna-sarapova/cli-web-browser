# Self-made browser

## Task

1. You have to write a command line program, using [go2web](go2web) as a starting point;
2. The program should implement the following CLI:
  ```
  go2web -u <URL>         # make an HTTP request to URL and print the response
  go2web -s <search-term> # search the term using your favorite search engine and print top 10 results
  go2web -h               # show help
  ```
3. The responses from requets should be human-readable (e.g. no HTML tags in the output)
3. Add another option to the program, to impress that biiiig investor.

## Special conditions

You can use any programming language, but not the built-in/third-party libraries for making HTTP requests. You can't build a GUI application.


## Run

```
go2web.py -u google.com    
```
The command will send a request to the specified URL and will print the response message
```
go2web.py -h                
```
This command  will print the existing commands