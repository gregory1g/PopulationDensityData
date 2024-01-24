<a href="https://github.com/camaraproject/PopulationDensityData/commits/" title="Last Commit"><img src="https://img.shields.io/github/last-commit/camaraproject/PopulationDensityData?style=plastic"></a>
<a href="https://github.com/camaraproject/PopulationDensityData/issues" title="Open Issues"><img src="https://img.shields.io/github/issues/camaraproject/PopulationDensityData?style=plastic"></a>
<a href="https://github.com/camaraproject/PopulationDensityData/pulls" title="Open Pull Requests"><img src="https://img.shields.io/github/issues-pr/camaraproject/PopulationDensityData?style=plastic"></a>
<a href="https://github.com/camaraproject/PopulationDensityData/graphs/contributors" title="Contributors"><img src="https://img.shields.io/github/contributors/camaraproject/PopulationDensityData?style=plastic"></a>
<a href="https://github.com/camaraproject/PopulationDensityData" title="Repo Size"><img src="https://img.shields.io/github/repo-size/camaraproject/PopulationDensityData?style=plastic"></a>
<a href="https://github.com/camaraproject/PopulationDensityData/blob/main/LICENSE" title="License"><img src="https://img.shields.io/badge/License-Apache%202.0-green.svg?style=plastic"></a>

# Population Density Data
Repository to describe, develop, document and test the Population Density Data API family

## Scope
* Service APIs for “Population Density Data” (see APIBacklog.md)  
* It provides the customer with the ability to:  
  * The service enables developers with the capability to get dynamic population density data in a specific area for a future date&time, considering anonymized information of the network connected devices in the requested area at the flight time.
    * Use Case (1): Providing BVLOS flight the data to meet SORA 2.5 requirements in terms of intrinsic Ground Risk Class (iGRC).
    * Use Case (2): Providing data to identify if the ground risk class for a given drone flight is acceptable for the time of the flight, or an alternative time should be considered to lower the risk.
  * Service Inputs: Area of the interest. Date & time (future) range.
  * Service Outputs: maximum, average and minimum population density value for the given area, and interval corresponding to the valid range of that value. (space and time maps).
  * NOTE: The scope of this API family should be limited (at least at a first stage) to 4G and 5G.  
* Describe, develop, document and test the APIs (with 1-2 Telcos)  
* Started: December 2023
* Location: virtually  

## Meetings
* Meetings are held virtually [Click here to join (MSTeams)](https://teams.microsoft.com/l/meetup-join/19%3ameeting_MTVjODg5OGUtMzEwYi00OTliLWI0YmUtZDhkODIzYWQ2NjZk%40thread.v2/0?context=%7b%22Tid%22%3a%229744600e-3e04-492e-baa1-25ec245c6f10%22%2c%22Oid%22%3a%22513e8b46-b8fc-417f-af4d-8d0846d5f626%22%7d)
* Schedule: bi-weekly, Wednesday, 14:00 Europe/Amsterdam (CET) (13:00 UTC, 12:00 UTC during European DST).

  For date/time of next meeting see [previous meeting minutes](https://github.com/camaraproject/PopulationDensityData/tree/main/documentation/MeetingMinutes).


## Contributorship and mailing list
* To subscribe / unsubscribe to the mailing list of this Sub Project and thus be / resign as Contributor please visit <https://lists.camaraproject.org/g/sp-pdd>.
* A message to all Contributors of this Sub Project can be sent using <sp-pdd@lists.camaraproject.org>.
