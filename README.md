#Noise Complaint Dataset

### Context

This dataset contains all noise complaints calls that were received by the  city
police with complaint type "Loud music/Party" in 2016. The data contains the
time of the call, time of the police response, coordinates and part of the city.

This data should help match taxi rides from "New York City Taxi Trip Duration"
competition to the night rides of partygoers. 


### Content

The New York city hotline receives non-urgent community concerns, which are made
public by the city through NYC Open Data portal. The full dataset contains a
variety of complaints ranging from illegal parking to customer complaints. This
dataset focuses on Noise complaints that were collected in 2016  and indicate
ongoing party in a given neighborhood. 

**parties_in_nyc.csv:**<br />
 **Columns**:<br />
Created Date - time of the call <br />
Closed Date - time when ticket was closed by police <br />
Location Type - type of the location <br />
Incident Zip - zip code of the location <br />
City - name of the city (almost the same as the Borough field) <br />
Borough - administrative division of the city <br />
Latitude - latitude of the location <br />
Longitude - longitude of the location <br />
<br />
**test_parties and train_parties:**<br />
 **Columns**:<br />
id - id of the ride <br />
num_complaints - number of noise complaints about ongoing parties within ~500
meters and within 2 hours of pickup place and time <br />


### Acknowledgements

[https://opendata.cityofnewyork.us/][1] - NYC Open Data portal contains many
other interesting datasets
Photo by [Yvette de Wit][2] on [Unsplash][3]


### Inspiration

After a fun night out in the city majority of people are too exhausted to travel
by public transport, so they catch a cab to their home. I hope this data will
help the community to find the patterns in the data that will lead to better
solutions.


  [1]: https://opendata.cityofnewyork.us/
  [2]: https://unsplash.com/@yvettedewit
  [3]: https://unsplash.com/
