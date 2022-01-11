command for setting a volume o a container 
---------------------------------------------
docker run -p 3000:3000 -v /app/node_modules -v $(pwd):/app   d3d732cd4ee5

to run compose file
----------------------
docker-compose up --build

to remove compose filw
-------------------------
docker-compose down

docker attach to a specific container for STDIN STDOUT AND STDERR
----------------------------------------
docker attach f12e1da16ae9
