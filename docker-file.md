## 🐳 Docker Terminal Commands

### 🚀 Run Your First Container

**1. Check your Docker version**
Run this to ensure Docker is running and see which version you have installed.

```
 docker --version
```

**2. Test with Hello-World**
This command tells Docker to download a tiny test image from Docker Hub and run it. It will print a welcome message and then automatically exit.
<br />
```
 docker run hello-world
```
**3. Start a Nginx web server**
Here, you are telling Docker to run the Nginx web server.
- -d : Runs the container in the background (detached mode).
- -p 8080:80 : Maps port 8080 on your machine to port 80 inside the container.

```
 docker run -d -p 8080:80 nginx
```

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!TIP]
> Helpful advice for doing things better or more easily.
