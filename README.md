# GRPC Library
Library proto files for GRPC communication

# How to contribute
First, you need to run this command
```
make init
```

After that, you can create your project in directory `module`. For example, you want to create a project named `core-be-user-svc` then you can create a directory `core-be-user-svc` in `module` directory. After that, you can create your proto files in `core-be-user-svc` directory.

After completing your proto, you can run this command to generate your Golang files
```
MODULE=${module_name} make generate

// ex. if generate for user
MODULE=user make generate
```

Finally, you can commit your changes and create a pull request to this repository.