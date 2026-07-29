# HubSpot-Property-History-Cleaner
A Python script, built to "stack" the historical data of the HubSpot field values to make it easier to sort chronologically and trace changes.

Issue: HubSpot Property History exports come in a strange format. Where the list received would show you the list of objects and their IDs, but all the information is displayed to the right.
i.e. The columns would look something like Object ID, Email, Current Value, Changed By, Value (1), Changed By (1), Value (2), Changed By (2), and so on.
This makes it difficult to read if there had been multiple changes over time to one field.
