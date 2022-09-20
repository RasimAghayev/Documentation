# docker

<details>
   <summary>run</summary>
<p>
   
   [run](https://docs.docker.com/engine/reference/commandline/run/)
   
   
-t : Allocate a pseudo-tty
   
-i : Keep STDIN open even if not attached
   
-p : [Publish or expose port (-p, --expose)](https://docs.docker.com/engine/reference/commandline/run/#publish-or-expose-port--p---expose)

      
### Example - run
```shell
dokcer run node # image name
dokcer run -it node # image name
docker run -p 3000:80 33483ba #container name 3000 external port in use (localhost:3000) , 80 internal container port
```
</p>
</details>




<details>
   <summary>ps</summary>
<p>
   
   [ps](https://docs.docker.com/engine/reference/commandline/ps/)
   
   --all , -a  :  Show all containers (default shows just running)
   
### Example - ps
```shell
dokcer ps
dokcer ps -a
```
</p>
</details>

<details>
   <summary>build</summary>
<p>
   
   [run](https://docs.docker.com/engine/reference/commandline/build/)
   

      
### Example - run
```shell
dokcer run node
dokcer run -it node
```
</p>
</details>


# Dockerfile

<details>
   <summary>Dockerfile</summary>
<p>
   
   [builder](https://docs.docker.com/engine/reference/builder/)
 
### Example - run
```shell
dokcer build .
```
</p>
</p>
</details>
