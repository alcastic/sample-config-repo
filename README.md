# Sample Config Repo

## What contains this repository?
This repository contains property files for applications and environments.


## What is the compliance of the defined files?
Property files can be stored using the next the following paths format:

    ./{application}/{profile}[/{label}]
    ./{application}-{profile}.yml
    ./{label}/{application}-{profile}.yml
    ./{application}-{profile}.properties
    ./{label}/{application}-{profile}.properties

## What the idea behind this repository?
The defined configuration in this repository can be exposed using spring-cloud-config-server.
By example [sample-spring-cloud-config-server](https://github.com/alcastic/sample-spring-cloud-config-server)

## Why this extra work? Worth it?
The main idea is to create a `Config Server` to store and serve distributed configurations across multiple applications and environments in distributed system having a central place to manage configurations.