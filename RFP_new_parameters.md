# PROPOSED PARAMETERS FROM RFP TO BE ADDED TO ERA ONTOLOGY
## Problem setting

As part of RNE’s work supporting the IMs digitalising their network statement, RNE has been
contracted to study, define and propose additional infrastructure parameters which would be
needed for RINF to effectively cover the nature of the infrastructure part of the Rail-FacilitiesPortal. After comparison between the parameters of the RFP with those of the RINF Register of
Infrastructure and ERA Vocabulary, RNE proposed the following parameters to enrich ERA Ontology and as inputs for future developments of the RINF application.

## Proposed solution
# Classes
### Service Facility

Has super-classes: **Operational Point**

Description: A Service Facility is a facility that offers services to trains, primarily maintenance, loading, and refuelling.
A service facility is a facility that regulatory bodies may decide to exempt from operators if it meets the following conditions:

It is a service facility or service that does not have strategic importance for the functioning of the rail transport services market, particularly concerning the level of facility use, the type and volume of traffic potentially impacted, and the types of services offered;
It is operated or provided in a competitive market environment with multiple competitors offering comparable services;
Its exemption from this Regulation would prevent negative impacts on the functioning of the service facility market.

Regulation: n/a

In domain of: **Facility Type**, **Facility Owner**

In range of:

# Object-Properties
### Facility Owner

Has domain: **Service Facility**

Has range: **org:Organization**

Description: The owner of the service facility.

Regulation: n/a

# Data-Properties
### Facility Type

Has domain: Service Facility

Has range: *Integer*

Description: A type of Service Facility, identified by a number. The possible values are:

  1 = Passenger station - Train station for passenger traffic, equipped with specific facilities for the access of the passengers and providing related services.
  
  2 = Intermodal terminal - Location which provides the space, equipment and operational environment under which the loading units (freight containers, swap bodies, semi-trailers or trailers) transfer takes place.
  
  3 = Multifunctional rail terminal - 
  
  4 = Public siding - Tracks branching off running main tracks/lines. 
  
  5 = Private siding - Privately operated pieces of rail infrastructure, connecting loading facilities (normally industry and other manufacturing sites) to the public rail network.
  
  6 = Marshalling yard - Site especially equipped with a number of tracks or other equipment for railway vehicle marshalling (switching) operations. Sometimes also referred to as classification yard.
  
  7 = Storage siding - Sidings specifically dedicated to temporary parking of railway vehicles between two assignments.
  
  8 = Maintenance facility
  
  9 = Other technical facility
  
  10 = Relief facility
  
  11 = Refueling facility
  
  12 = Mobile service provider

Regulation: Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 1 of Reg. 2017/2177)
