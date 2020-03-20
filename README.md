# _Hair Salon_

#### _Epicodus C# Week 4 solo project, 3/20/2020_

#### By _Matt Taylor_

## Description

_This application project is an exercise in C# using the MVC framework._

## Behavior Driven Development
| Behavior | Input | Output |
|----|----|-----|
| Web application loads | 'dotnet run' | Page is displayed |
| User adds a new stylist | click link, fill form | New stylist is added to list |
| Application displays list of input stylists | click link | List is shown of stylists with details |
| User adds a new client | click link, fill form | New client is added to list, by stylist |
| Application displays list of input clients by stylist | click on stylist link | Client list is displayed |
| Application displays client details | click on client link | Client details are displayed |

## MySql

CREATE DATABASE `matt_taylor`

CREATE TABLE `clients` (  
  `ClientId` int(11) NOT NULL AUTO_INCREMENT,  
  `ClientName` varchar(255) DEFAULT NULL,  
  `PhoneNumber` varchar(255) DEFAULT NULL,  
  `StylistId` int(11) DEFAULT NULL,  
  PRIMARY KEY (`ClientId`)  
)

CREATE TABLE `stylists` (  
  `StylistId` int(11) NOT NULL AUTO_INCREMENT,  
  `Specialty` varchar(255) DEFAULT NULL,  
  PRIMARY KEY (`StylistId`)  
)

## Setup/Installation Requirements

* Open Terminal
* Type ``$ git clone https://github.com/mtaylorpdx/HairSalon.Solution``
* Navigate to the directory HairSalon.Solution/HairSalon
* Type ``$ dotnet run``
* Open your browser and enter the address ``localhost:5000``

## Support and contact details

Email [@Matt Taylor](mailto:me@email.com)

## Technologies Used

* Git
* C#
* .NET Core
* ASP.NET Razor
* MySql
* Entity Framework Core

### License

*Licensed under the MIT License*

Copyright (c) 2020 **_Matt Taylor_**