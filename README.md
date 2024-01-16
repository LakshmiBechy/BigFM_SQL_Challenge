# 92.7 BIG FM radio network - SQL Challenge by Digits n Data

## Challenge
The challenge is to craft SQL queries to extract insights from the 92.7 BIG FM radio network database.

### Tables
  - Stations Table:
    StationID (INT),
    StationName (VARCHAR(255)),
    Location (VARCHAR(255)),
    Frequency (DECIMAL(5,2)),
    LaunchDate (DATE)
    
-   Hosts Table:
    HostID (INT),
    HostName (VARCHAR(255)),
    ShowCount (INT),
    JoinDate (DATE)

- Shows Table:
    ShowID (INT),
    ShowName (VARCHAR(255)),
    HostID (INT),
    StationID (INT),
    LaunchDate (DATE)

- Partnerships Table:
  PartnershipID (INT),
  PartnerName (VARCHAR(255)),
  PartnershipType (VARCHAR(100)),
  StartDate (DATE),
  EndDate (DATE)
  
- ShowPartnerships Table:
  ShowID (INT),
  PartnershipID (INT)

- Awards Table:
  AwardID (INT),
  AwardName (VARCHAR(255)),
  Year (INT),
  ShowID (INT)

- OnlinePresence Table:
  PresenceID (INT),
  PlatformName (VARCHAR(255)),
  Link (VARCHAR(255)),
  LaunchDate (DATE)
 

### Questions
- 1)Retrieve all stations in the "East" region?
- 2)List all shows hosted by "Vrajesh Hirjee"?
- 3)Count the number of awards each show has won?
- 4)Find shows that have partnerships with "Spotify"?
- 5)Retrieve hosts who joined before 2010?
- 6)List the shows and their launch dates in descending order of launch date?
- 7)Find the total count of shows for each host?
- 8)Show the online presence platforms with their links?
- 9)Retrieve the stations in the "South" region launched after 2010?
- 10)Rank hosts based on the number of shows they have hosted?

### Concepts Used
    - Aggregated Functions: SUM, COUNT
    - Filtering Rows: WHERE
    - Combining Tables: JOINS
    - Grouping Results: GROUP BY
    - Sorting Results: ORDER BY
    - Rank Functions

### Additional Queries performed:
   - Explored subqueries - Years with the highest number of awards
   - Advanced Joins - To list out award winning shows detailing their partnership information

### Tools Used:
    - MySQL: For comprehensive data analysis.
    - Canva: For presenting insights.

Challenge Link: https://nitish2162001.github.io/webpa/
