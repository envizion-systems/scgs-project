#5.	Actual sign in to shift

This endpoint will accept time clock data and apply it to the clocked in element of the passed shift id. If you pass multiple sign-in calls, each will be logged to the database

### Required Permissions
In order to use the /v3/send endpoint, your consumer key must have the "Modify" permission.


### Method URL
```
{BASE_URL}/timecards/<shiftid>/clockon
```

### Parameters

```
{
  "clockdate": "22/10/2020",
  "clocktime": "14:05",
  "lat": "-35.497978849677",
  "long": "151.893723000"
}
```
