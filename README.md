# rades
## A clustered, reactive, automated server solution.

[![experimental](http://badges.github.io/stability-badges/dist/experimental.svg)](http://github.com/badges/stability-badges)

# Description

rades means rust + hades. hades is an experimental game server sulotion based on Node.JS.   
since the name `hades` has been taken, I use `rades` now for the new project.  
rust is not included now(maybe later, but no plan). If you want a Rust + Typescript framework, deno maybe your first choice.   

# Why ?

I think a sulotion should be very simple to use. So try it as 
* a simple framework to learn server programming
* a quick prototype for server logic 

# Features

* clusterd and scalable server progress
* simple request based on proxy entity
* simple rpc invoke based on entity system
* full schema driven development
* auto orm mapping for data storage
* rades-cli for your server codes/configures management
* multile clients support
  * lua
  * javascript
  * python
  * c++
  * c#

# Roadmap

## 0.3.0 basic architecture
## 0.4.0 modules indepedency
* rades-core
* rades-protocol
* rades-schema
* rades-message
* rades-rpc
* rades-util

## 0.5.0 rades-cli
