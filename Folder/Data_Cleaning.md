# Hotel Management Data Analysis focusing on revenue and loss through canceled bookings
----


* ---showing all columns
```
Select *
From dbo.Hotel
```

* --- checking for nulls
```
select *
from dbo.hotel
where [Booking Date] is null
```
--- No nulls for booking Date

```
select *
from dbo.hotel
where Hotel is null
```
---No nulls for column Hotel

```
![#f03c15]select`#f03c15` *
from dbo.hotel
where [Arrival Date] is null
```
---No nulls for Arrival date

Here is the image of the dashboard.
![Dashboard](https://github.com/HopeVictor/SQL-Projects/blob/main/Folder/OIP.webp)

