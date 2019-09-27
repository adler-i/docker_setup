## Rails Application Setup Using Docker

```
   git@github.com:adler-i/docker_setup.git
```

* Build the Docker image.
  
    ```
    docker-compose build
    ```
* Set up your app's database.

  ```
  docker-compose run web rake db:setup
  ```
  
* Bring them all up.
  
    ```
    docker-compose up
    ```
    
* Other usefull commands
   
      docker-compose run web rails console
      docker-compose run web bash
      docker-compose run web rake routes
      docker-compose run web rspec
      docker-compose run web bundle

