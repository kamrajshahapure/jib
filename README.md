# Hello World Java Project to Create Docker Image Using Java Image Builder (JIB)

  ### Setup
  This doesn't require much setup if you are already running a Maven based build for your project.
  
  The only change you'd need is inside the `settings.xml` inside your `.m2` folder 
  In `settings.xml` you'll need to add a `servers` section to add your credentials of dockerhub/GCR or any container registry that you want to push your images to.
  
  Here is the snippet for configuring dockerhub registry with Maven in `settings.xml`
  
  ```
  <servers>
    <server>
      <id>registry.hub.docker.com</id>
      <username>USERNAME</username>
      <password>PASSWORD</password>
    </server>
  </servers>
  ```
  
  
