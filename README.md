
# for build
    docker build --tag exampleproject .

# for container start 
    docker run --name example -d -p 8005:80 exampleproject
 
# for container start with name "example"
	docker container start example

# for container stop with name "example"  
	docker container stop example

# for test
go to
    http://localhost:8005/api/values
if you see this json
    [ "value1", "value2" ]
    
success
