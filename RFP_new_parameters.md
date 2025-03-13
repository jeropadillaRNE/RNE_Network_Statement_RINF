# PROPOSED PARAMETERS FROM RFP TO BE ADDED TO ERA ONTOLOGY
## Problem setting

As part of RNE’s work supporting the IMs digitalising their network statement, RNE has been
contracted to study, define and propose additional infrastructure parameters which would be
needed for RINF to effectively cover the nature of the infrastructure part of the Rail-FacilitiesPortal. After comparison between the parameters of the RFP with those of the RINF Register of
Infrastructure and ERA Vocabulary, RNE proposed the following parameters to enrich ERA Ontology and as inputs for future developments of the RINF application.

## Proposed solution
# Classes
### Service Facility
Has super-classes: Operational Point
Description: A Service Facility is a facility that offers services to trains, primarily maintenance,
loading, and refuelling.
Regulation: n/a
In domain of: Facility Type, Facility Owner
In range of:
# Object-Properties
### Facility Owner
Has domain: Service Facility
Has range: org:Organization
Description: The owner of the service facility.
Regulation: n/a
2
# Data-Properties
### Facility Type
Has domain: Service Facility
Has range: Integer
Description: A type of Service Facility, identified by a number. The possible values are:
1 = Passenger station
2 = Intermodal terminal
3 = Multifunctional rail terminal
4 = Public siding
5 = Private siding
6 = Marshalling yard
7 = Storage siding
8 = Maintenance facility
9 = Other technical facility
10 = Relief facility
11 = Refueling facility
12 = Mobile service provider
Regulation: n/a
