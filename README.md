# Terraform-1-Docker

Learn terraform through Hashicorp Docker tutorials

## Description

This is a terraform project that creates a docker container with a simple web server.
it allows you to learn how to provision and manager docker container and images using
terraform main features such as variables, outputs, providers and resources.

## Usage

1. Start the devcontainer to get the required tools and dependencies.
2. Go into the src folder then run the following commands:

```bash
terraform plan
```

it will check your current docker configuration and show you what will be created or updated.

3. Then you can run the following command to make the changes:

```bash
terraform apply
```

## References

- [Tutorial](https://developer.hashicorp.com/terraform/tutorials/docker-get-started)
