# Requested REST API: Confirmed Roster

Given a start date and an end date, return all the shifts in the period

### Method URL
```
{BASE_URL}/timecards?start=dd/mm/yyyy&end=dd/mm/yyyy
```

### Parameters


```
a.	Parameter: Start Date, End Date  
b.	Returns: 

  - PowerForce ID, 
  - Site Code, 
  - Employee Code, 
  - Start Time, 
  - End Time, 
  - Shift Confirmation, 
  - Actual Sign-In and 
  - Actual Sign-Out, Job Date
```