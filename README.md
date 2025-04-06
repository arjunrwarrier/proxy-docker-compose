TORUN: docker-compose up

TOSTOP: docker-compose down

TOSTOP&CLEAN: docker-compose down --rmi all --volumes --remove-orphans

### Use curl command to check if the proxy is working, check logs of both server and client containers

  `curl -x http://localhost:8080 http://httpforever.com/`

  To see multiple images loaded live, use localhost 8080 as proxy and load in browser :http://www.http2demo.io/
 
  `curl -x http://localhost:8080 http://www.http2demo.io/`
    
