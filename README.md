For pa5 you will need to make sure that you have a working system that can compile my code with makeFile. You would need to download both my makeFile and code to run my program. You would open your terminal and run make, then ./pa5 8080 (the specific port) and then a message should pop up saying (Proxy listening on port 8080). I used the example input and output provided on the assignment to test and ensure that my program worked how it was intended. So how I exaplained earlier you would first run make and then the name of my program name is pa5 and then we are working on port 8080. 
input:
make
./pa5 8080
output: 
Proxy listening on port 8080

Then opening a new terminal you would input: curl -x localhost:8080 http://example.com/

Output: <!doctype html><html lang="en"><head><title>Example Domain</title><meta name="viewport" content="width=device-width, initial-scale=1"><style>body{background:#eee;width:60vw;margin:15vh auto;font-family:system-ui,sans-serif}h1{font-size:1.5em}div{opacity:0.8}a:link,a:visited{color:#348}</style></head><body><div><h1>Example Domain</h1><p>This domain is for use in documentation examples without needing permission. Avoid use in operations.</p><p><a href="https://iana.org/domains/example">Learn more</a></p></div></body></html>
This output ensures that the procy is correctly forwarding and relaying responses. 

I'm making the assumption that you have a working linux system or a system that is able to process make so for me I built this on visual studios with eNet and SFML installed for our final cs 360 game. Also the required tools are installed gcc and make also making sure that port 8080 is not blocked by any security protections and provide a valid http when testing.  

So I am able to run my make file have pa5 running and then have that specific port open. AI implementation was documented to help me make the makeFile and other code developed in the handle_client as well as pulling concepts from my own client system created for our final project. 
