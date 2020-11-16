# Ruby on Rails Development Kit Containerized

## How to use?

```shell
docker-compose build
```
Now you should got an awesome and smart image named `rails-docker-starter_rails:latest`, you can specify ruby version and node version in Dockerfile according to your need.  
All you need to do is:  
Bind mount your container and run the rails command like so:  
```shell
rails new your-project-name
```

That's it. There you go. 😎  
Here is a more detailed [medium article](https://medium.com/@crazyoptimist/how-to-develop-rails-application-using-docker-a-present-for-rubyists-from-a-docker-fan-with-love-343b386a5528), just in case.  
Happy coding Rubyists!
