# Rust notebook

Hi - In the project are some loosely coupled project that i made during the course of me learning rust. I will continue to update anything worth archiving that can help a larger audience. 

List of items are categorized roughly as below. 

## Command line utilities

Rust is popular in its own way for writing utilities for command line. The clap library provides a neat way to extract arguments from any command line run programes / services / adapters etc. 

## Async and network 
In rust, async & await would need a lot of practise and in the folder you would see some examples of using ... 

 - Some simple usage of Async await - futures
 - Simple examples of Tokio run time, spawn  
 - TcpStream ( converting tcpstreams { sockets } as Streams ) & socket based client server exchange of a file
 - TcpUtils ( codecs ) based simple chat / echo server
 - Converting u8 vectors into streams.
 - [Someday] Websockets and tokio codecs 

## Concurrency & parallelism
- Threading support and simple usage of cross beam channels
- [Someday] Ray-on usage along with actix or rocket or warp. 

## Database
- A sample program that demonstracts CRUD with Postgresql using diesel.rs ORM adapter, migration of schema using diesel-cli. Sakila sample db is used as sample. I move some int2's around as int4s in the db schematic.
- [Someday] Noria, Neo4J and influxDB usage.

## General
Rust langauge samples for various concepts.

## Microservices
- actix-web-mongodb  is expected to demonstrate the usage of .. 
	- Mongo driver of rust (CRUD operations of a record. R2d2 polling is avoided since the connection polling is part of the mongodb rust driver.)
    - Actix web framework - CRUD APIs with db ( along with postman json )
    - Static serving of files 
- [Someday] Rocket, gRPC and warp 

