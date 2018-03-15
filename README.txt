alexlv
Alex Levenzon 308636141
ex2 http client
client.c - Implementation of basic http client
README.txt - A readme text file

This is an implenetation of basic http client that handels http requests by reciving an input from user,
translating it to the correct request and sending to the right server. If the address was correct,
the client will display the request response (html page, only header, error message).

In addition , the user will see his request in the format that will be sent to the server 
and after (if succeded) getting the response. will display it with the number of bytes that were received.

for compiling the project do:

gcc client.c -o client
client is the executable program.

the usage has to be in the following format:
./client [-h] [-d <time-Interval>] <URL>

the arguments can come in any order but the time interval should go with the '-d' argument.

URL only - will recieve the whole html file
-h - http header request. Will recieve only the header of the html file
-d - request with time limitations. Will recieve the html file only if the page was changed during the given period.

The format of the URL has to be like this - http://<your address with/without port>/<optional path>
The format of time request has to be  <day>:<hr>:<min>

Hope that you will enjoy this small project that took all of my time to complete on time!!
:)