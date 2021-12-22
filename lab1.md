### Lab1
                
1. Install docker on your VM.
2. Check client version.
3. Check server version.
4. Download busybox image on your machine (just DOWNLOAD).
5. Launch a container based on "ubuntu/apache2" image, expose it on your local port 8005.
6. Launch a container based on nginx, run it in detached mode, publich its port to your physical port 8006, name it "my-ng-con".
7. Launch a container based on nginx:1:17, It is not going to work! Why ?
8. Run the following command:
```bash
docker container run -d -p 8006:80 nginx --name cnt1
```
It is not goign to run, fix it .
9. Launch a container based on httpd, expose it's port on 9000 locally, name it "my_httpd" and update it's home page's content.
10. Remove my_httpd container without passing by stopping phase.
11. Launch a container based on httpd, expose it's port on 9000 locally, name it "my_httpd" (the same as 10.) do you find the modified home page ?
