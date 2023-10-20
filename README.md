

# <h1 align = "center">Hotel Room App</h1>
___ 
<p align="center">
<a href="Java url">
    <img alt="Java" src="https://img.shields.io/badge/Java->=8-darkblue.svg" />
</a>
<a href="Maven url" >
    <img alt="Maven" src="https://img.shields.io/badge/maven-3.1.3-brightgreen.svg" />
</a>
<a href="Spring Boot url" >
    <img alt="Spring Boot" src="https://img.shields.io/badge/Spring Boot-3.0.6-brightgreen.svg" />
</a>
</p>

---

<p align="left">

<!-- Project Description -->
## Overview
<p align="center">This project, named "Room App" is a robust Spring Boot application designed for managing Room data efficiently. It provides a set of API endpoints that allow you to perform various operations on Room records, such as adding, retrieving, updating, and deleting Room information. 
</p>

<!-- Table of Contents -->
## Table of Contents
1. [Technologies Used](#technologies-used)
2. [Key Features](#key-features)
3. [Usage](#usage)
4. [API reference](#api-reference)
5. [Acknowledgments](#acknowledgments)

<!-- Technologies Used -->
## Technologies Used
- Java 8
- Spring Boot
- Spring Web Initializer
- Maven
- Spring Web Dependency
- H2 Database


<!-- Key Features -->
## Key Features
- Add Room
- Get All Rooms.
- Get Room By Id.
- Delete Room By Id.
- Update Room Id

## Controller API

- @Postmapping ("room")
- @GetMapping ("rooms")
- @GetMapping("rooms/AC/or/available")
- @DeleteMapping("rooms/ids")
- @GetMapping("rooms/price/{price}")

## Model entity

-  Integer roomId;
- Integer roomNumber;
- Type roomType;
-  boolean roomAvailable;
- double roomPrice;

<!-- Usage -->
## Usage
- Access the application at http://localhost:8080.
- Use the provided API endpoints to manage your Room App.

### Controller:
- It consists of a class named APIController which basically controls the flow of data.
- @RestController annotation is used to make the APIController as a controller layer.
- We perform the CRUD operations such as @PostMapping , @GetMapping ,  @DeleteMapping.

## Service:

- All the methods made related to controller class.

<!-- Acknowledgments -->
## Acknowledgments
- Thank you to the Spring Boot and Java communities for providing excellent tools and resources.
