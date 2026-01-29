
```dataview
TABLE Significance, EventType as "Event Type", StartDate as "Start Date", EndDate as "End Date"
FROM "3 - Equilibrium/World Building/Timeline/Historical Entries"
WHERE contains(file.tags, "TimelineEquilibrium")
SORT StartDate ASC
```
