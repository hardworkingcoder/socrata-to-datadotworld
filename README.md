# socrata-to-datadotworld

Example of installing socrata-to-datadotworld and then copying https://data.seattle.gov/Transportation/Traffic-Flow-Counts/7svg-ds5z/data:

```
pip install socratatodatadotworld
dw configure
socrata-to-datadotworld
Your data.world username: hardworkcoder
The Socrata domain such as data.seattle.gov: data.seattle.gov
The Socrata dataset id which you get from the url. It is eight characters and has a dash. For example for https://data.seattle.gov/Public-Safety/Seattle-Real-Time-Fire-911-Calls/kzjm-xkqj/data the id is kzjm-xkqj: 7svg-ds5z
```
