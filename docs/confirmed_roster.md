# Requested REST API: Confirmed Roster

This endpoint is to accept whether the employee has accepted or rejected the shift.

### Required Permissions

In order to use the {BASE_URL}/timecards/ endpoint, your consumer key must have the "Modify" permission.

### Method URL
```
{BASE_URL}/timecards/<shiftid>/confirm
```

### Parameters
```
{"action_results":[true],"status":1}
```