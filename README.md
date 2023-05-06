# USummerSchoolTask2023
## Test task for summer practise in company UDV in 2023.

### Docker Engine installation: 
Just follow this instructions:
https://docs.docker.com/engine/install/ubuntu/

### Application installation on Ubuntu:
1. Go to the folder where you have all files from this repository to pull required images, build application image and then create and run a container:
```sudo docker compose up -d``` 
> - we use Docker compose of version 2
> - option '-d' meanes 'detached', for starting your container at the background)

2. **Profit!** Now the container is working in docker!
You can see nginx welcome page with ```localhost:8080``` and index.php page with ```localhost:8080/index.php```. 

Well, you also can replace 'localhost' with public IP of your VPS where this docker container has being deployed