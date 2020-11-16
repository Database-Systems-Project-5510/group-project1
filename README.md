# Introduction

## Index
* [Use Case for Rating Systems](#use-case-for-rating-systems)
* [Business Rules](#business-rules)
* [EERD](#eerd)
* [MySQL Queries](#mysql-queries)
* [Stored Procedure](#stored-procedure)
* [Description of Future Work](#description-of-future-work)
* [MySQL Dump](#mysql-dump)
* [PowerPoint Video Link](#powerpoint-video-link)


## Use Case for Rating Systems

## Business Rules

Here is some basic information on the existing database prototype:

1. Persons (campus faculty, staff, students) have accounts in the system with personid (PK), name, email, cell, etc. For faculty we also keep title, highest degree, and degree college. For staff we keep Position and AdminYorN. For students we keep GradYear and major plus type (undergraduate, graduate). Only faculty, staff and students are included.
2. We have Locations which are spots on campus where food can be delivered. Some examples are dorms, the student center, and approved classroom buildings. LocationID, LocationName, LocationAddress and (optional) Latitude and Longitude are maintained in the database. Additionally a food delivery drop-off point is included (designated place for meeting or delivering food in the location- this can be a brief description).
3. Persons can also be drivers (delivery personnel which have to be approved). Drivers have licensenumber and datehired plus ratings. You may also want to keep vehicle information (relative to the vehicle that the driver uses).
   - UNCC will start with 8 approved delivery personnel - the system is in test mode. You can assume all individuals have been cleared and they can be included in the database.
   - All delivery personnel are students.
4. There is a flat fee of $5 for each delivery. A person orders food one to many times. An individual delivery is tied to one and only one person for the order. The order is for one and only one restaurant. For the items on the order we will only need to keep the total price and delivery charge, along with the driver and delivery times. There should also be a unique identifier (ID) that ties to the id for the order at the individual restaurant. You can assume that the actual items on the order need to come from the restaurant database.
5. Food providers or restaurants have to be approved in order to be included in the database. You can include an ID, location, schedule, and a link to the website along with other attributes you may identify.
6. You are adding a rating system which does not exist in the database.
7. The database will serve as an important data collection source providing valuable information about nutrition and eating habits of campus community members.

## EERD

## MySQL Queries

## Stored Procedure

## Description of Future Work

## MySQL Dump

## PowerPoint Video Link
  

  
  
  

  
  
