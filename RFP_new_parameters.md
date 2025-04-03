# PROPOSED PARAMETERS FROM RFP TO BE ADDED TO ERA ONTOLOGY
## Problem setting

As part of RNE’s work supporting the IMs digitalising their network statement, RNE has been
contracted to study, define and propose additional infrastructure parameters which would be
needed for RINF to effectively cover the nature of the infrastructure part of the Rail-FacilitiesPortal. After comparison between the parameters of the RFP with those of the RINF Register of
Infrastructure and ERA Vocabulary, RNE proposed the following parameters to enrich ERA Ontology and as inputs for future developments of the RINF application.

## Proposed solution
# Classes
## Service Facility

Represents a facility that offers services to trains.

**IRI**: http://data.europa.eu/949/ServiceFacility

### Is a

* http://data.europa.eu/949/OperationalPoint

### Has Properties

* **Facility Type** - A type of Service Facility, identified by a number.
  
* **Facility Owner** - The owner of the service facility.

### Additional Information

**General explanation**:

The installation, including ground area, building and equipment, which has been specially arranged, as a whole or in part, to allow the supply of one or more services referred to in points 2 to 4 of Annex II.

**Regulation**: n/a

# Object-Properties
## Facility Owner
The owner of the service facility.
### General Information
**Number**: 1.1.1.5.1.1
**XML Name**: SF_Owner
**Deadline**:  xx

### Data Format
* **Data Presentation**
[Organization](https://linkedvocabs.org/data/era-ontology/3.1.0/appGuide/index-en.html#Organization)
* **Taxonomy Reference**
http://data.europa.eu/949/facilityOwner

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None
	
### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

# Data-Properties
### Facility Type

A type of Service Facility, identified by a number.
### General Information
**Number**: 1.1.1.5.1.2
**XML Name**: SF_Type
**Deadline**:  xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/facilityType
* **Values**
| Code | Value |
|------|-------|
| 1    | 1     |
| 2    | 2     |
| 3    | 3     |
| 4    | 4     |
| 5    | 5     |
| 6    | 6     |
| 7    | 7     |
| 8    | 8     |
| 9    | 9     |
| 10   | 10    |
| 11   | 11    |
| 12   | 12    |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None
	
### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	The possible values are:

  1 = Passenger station - Train station for passenger traffic, equipped with specific facilities for the access of the passengers and providing related services.
  
  2 = Intermodal terminal - Location which provides the space, equipment and operational environment under which the loading units (freight containers, swap bodies, semi-trailers or trailers) transfer takes place.
  
  3 = Multifunctional rail terminal - 
  
  4 = Public siding - Any track(s) within an operational point which is not used for operational routing of a train.

  5 = Private siding - Privately operated pieces of rail infrastructure, connecting loading facilities (normally industry and other manufacturing sites) to the public rail network.
  
  6 = Marshalling yard - Site especially equipped with a number of tracks or other equipment for railway vehicle marshalling (switching) operations. Sometimes also referred to as classification yard.
  
  7 = Storage siding - Sidings specifically dedicated to temporary parking of railway vehicles between two assignments.
  
  8 = Maintenance facility - 
  
  9 = Other technical facility
  
  10 = Relief facility
  
  11 = Refueling facility
  
  12 = Mobile service provider

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 1 of Reg. 2017/2177)


## id
Description for id.
### General Information
**Number**: None
**XML Name**: id
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## mainDataSource
Description for mainDataSource.
### General Information
**Number**: None
**XML Name**: mainDataSource
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## facilityType
Description for facilityType.
### General Information
**Number**: None
**XML Name**: facilityType
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## facilityName
Description for facilityName.
### General Information
**Number**: None
**XML Name**: facilityName
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## areaSeaport
Description for areaSeaport.
### General Information
**Number**: None
**XML Name**: areaSeaport
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## areaInlandPort
Description for areaInlandPort.
### General Information
**Number**: None
**XML Name**: areaInlandPort
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## areaFreightVillage
Description for areaFreightVillage.
### General Information
**Number**: None
**XML Name**: areaFreightVillage
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## exempted
Description for exempted.
### General Information
**Number**: None
**XML Name**: exempted
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## linkToAdditionalDocuments
Description for linkToAdditionalDocuments.
### General Information
**Number**: None
**XML Name**: linkToAdditionalDocuments
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## purposeOfSfDeclaration
Description for purposeOfSfDeclaration.
### General Information
**Number**: None
**XML Name**: purposeOfSfDeclaration
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## briefPresentation
Description for briefPresentation.
### General Information
**Number**: None
**XML Name**: briefPresentation
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## operatorName
Description for operatorName.
### General Information
**Number**: None
**XML Name**: operatorName
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## operator
Description for operator.
### General Information
**Number**: None
**XML Name**: operator
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## operatorType
Description for operatorType.
### General Information
**Number**: None
**XML Name**: operatorType
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## operatorOtherType
Description for operatorOtherType.
### General Information
**Number**: None
**XML Name**: operatorOtherType
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## operatorContact
Description for operatorContact.
### General Information
**Number**: None
**XML Name**: operatorContact
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## operatorPhone
Description for operatorPhone.
### General Information
**Number**: None
**XML Name**: operatorPhone
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## operatorFax
Description for operatorFax.
### General Information
**Number**: None
**XML Name**: operatorFax
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## operatorEmail
Description for operatorEmail.
### General Information
**Number**: None
**XML Name**: operatorEmail
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## operatorWebsite
Description for operatorWebsite.
### General Information
**Number**: None
**XML Name**: operatorWebsite
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## facilityOwner
Description for facilityOwner.
### General Information
**Number**: None
**XML Name**: facilityOwner
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## ownerType
Description for ownerType.
### General Information
**Number**: None
**XML Name**: ownerType
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## ownerOtherType
Description for ownerOtherType.
### General Information
**Number**: None
**XML Name**: ownerOtherType
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## operatorsRelation
Description for operatorsRelation.
### General Information
**Number**: None
**XML Name**: operatorsRelation
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## sfDataValidUntil
Description for sfDataValidUntil.
### General Information
**Number**: None
**XML Name**: sfDataValidUntil
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## sfDataUpdateProcedure
Description for sfDataUpdateProcedure.
### General Information
**Number**: None
**XML Name**: sfDataUpdateProcedure
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## dateForUpdate
Description for dateForUpdate.
### General Information
**Number**: None
**XML Name**: dateForUpdate
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## applyCompliance
Description for applyCompliance.
### General Information
**Number**: None
**XML Name**: applyCompliance
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## complianceConfirmed
Description for complianceConfirmed.
### General Information
**Number**: None
**XML Name**: complianceConfirmed
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## locomotiveCleaning
Description for locomotiveCleaning.
### General Information
**Number**: None
**XML Name**: locomotiveCleaning
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## wagonCleaning
Description for wagonCleaning.
### General Information
**Number**: None
**XML Name**: wagonCleaning
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## locomotiveParking
Description for locomotiveParking.
### General Information
**Number**: None
**XML Name**: locomotiveParking
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## wagonParking
Description for wagonParking.
### General Information
**Number**: None
**XML Name**: wagonParking
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## locomotiveRepairMaintenanceLight
Description for locomotiveRepairMaintenanceLight.
### General Information
**Number**: None
**XML Name**: locomotiveRepairMaintenanceLight
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## locomotiveRepairMaintenanceHeavy
Description for locomotiveRepairMaintenanceHeavy.
### General Information
**Number**: None
**XML Name**: locomotiveRepairMaintenanceHeavy
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## wagonRepairMaintenanceLight
Description for wagonRepairMaintenanceLight.
### General Information
**Number**: None
**XML Name**: wagonRepairMaintenanceLight
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## wagonRepairMaintenanceHeavy
Description for wagonRepairMaintenanceHeavy.
### General Information
**Number**: None
**XML Name**: wagonRepairMaintenanceHeavy
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## technicalInspectionOfRollingStock
Description for technicalInspectionOfRollingStock.
### General Information
**Number**: None
**XML Name**: technicalInspectionOfRollingStock
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## refuelling
Description for refuelling.
### General Information
**Number**: None
**XML Name**: refuelling
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## shunting
Description for shunting.
### General Information
**Number**: None
**XML Name**: shunting
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## provisionEmergencyEquipment
Description for provisionEmergencyEquipment.
### General Information
**Number**: None
**XML Name**: provisionEmergencyEquipment
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## securityServices
Description for securityServices.
### General Information
**Number**: None
**XML Name**: securityServices
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## tractionCurrent
Description for tractionCurrent.
### General Information
**Number**: None
**XML Name**: tractionCurrent
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## accessToTelecommunicationNetworks
Description for accessToTelecommunicationNetworks.
### General Information
**Number**: None
**XML Name**: accessToTelecommunicationNetworks
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## provisionSupplementaryInformation
Description for provisionSupplementaryInformation.
### General Information
**Number**: None
**XML Name**: provisionSupplementaryInformation
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## otherServices
Description for otherServices.
### General Information
**Number**: None
**XML Name**: otherServices
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## descriptionOfServices
Description for descriptionOfServices.
### General Information
**Number**: None
**XML Name**: descriptionOfServices
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## timetableServiceTrains
Description for timetableServiceTrains.
### General Information
**Number**: None
**XML Name**: timetableServiceTrains
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## facilityCertificates
Description for facilityCertificates.
### General Information
**Number**: None
**XML Name**: facilityCertificates
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## loadingUnloadingTranshipment
Description for loadingUnloadingTranshipment.
### General Information
**Number**: None
**XML Name**: loadingUnloadingTranshipment
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## loadingUnitCleaning
Description for loadingUnitCleaning.
### General Information
**Number**: None
**XML Name**: loadingUnitCleaning
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## loadingUnitFumigationDisinfection
Description for loadingUnitFumigationDisinfection.
### General Information
**Number**: None
**XML Name**: loadingUnitFumigationDisinfection
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## loadingUnitRepairMaintenance
Description for loadingUnitRepairMaintenance.
### General Information
**Number**: None
**XML Name**: loadingUnitRepairMaintenance
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## loadingUnitVentilation
Description for loadingUnitVentilation.
### General Information
**Number**: None
**XML Name**: loadingUnitVentilation
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## orderPickingWarehousing
Description for orderPickingWarehousing.
### General Information
**Number**: None
**XML Name**: orderPickingWarehousing
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## storageContainersGeneralCargo
Description for storageContainersGeneralCargo.
### General Information
**Number**: None
**XML Name**: storageContainersGeneralCargo
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## storageDangerousGoods
Description for storageDangerousGoods.
### General Information
**Number**: None
**XML Name**: storageDangerousGoods
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## storageRidClasses
Description for storageRidClasses.
### General Information
**Number**: None
**XML Name**: storageRidClasses
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## storageHandlingReefers
Description for storageHandlingReefers.
### General Information
**Number**: None
**XML Name**: storageHandlingReefers
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## stuffingStripping
Description for stuffingStripping.
### General Information
**Number**: None
**XML Name**: stuffingStripping
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## containerLashing
Description for containerLashing.
### General Information
**Number**: None
**XML Name**: containerLashing
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## weighingWagonsLoadingUnits
Description for weighingWagonsLoadingUnits.
### General Information
**Number**: None
**XML Name**: weighingWagonsLoadingUnits
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## containerSalesLeasing
Description for containerSalesLeasing.
### General Information
**Number**: None
**XML Name**: containerSalesLeasing
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## customsClearance
Description for customsClearance.
### General Information
**Number**: None
**XML Name**: customsClearance
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## trucking
Description for trucking.
### General Information
**Number**: None
**XML Name**: trucking
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## tailormadeContractsDangerousGoods
Description for tailormadeContractsDangerousGoods.
### General Information
**Number**: None
**XML Name**: tailormadeContractsDangerousGoods
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## tailormadeContractsAbnormalTrains
Description for tailormadeContractsAbnormalTrains.
### General Information
**Number**: None
**XML Name**: tailormadeContractsAbnormalTrains
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## trainBoardingDeboarding
Description for trainBoardingDeboarding.
### General Information
**Number**: None
**XML Name**: trainBoardingDeboarding
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## ticketingServices
Description for ticketingServices.
### General Information
**Number**: None
**XML Name**: ticketingServices
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## assistanceForPersonsWithReducedMobility
Description for assistanceForPersonsWithReducedMobility.
### General Information
**Number**: None
**XML Name**: assistanceForPersonsWithReducedMobility
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## lostAndFound
Description for lostAndFound.
### General Information
**Number**: None
**XML Name**: lostAndFound
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## luggageStoring
Description for luggageStoring.
### General Information
**Number**: None
**XML Name**: luggageStoring
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## waitingAreasAndWeaterProtection
Description for waitingAreasAndWeaterProtection.
### General Information
**Number**: None
**XML Name**: waitingAreasAndWeaterProtection
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## iceProtection
Description for iceProtection.
### General Information
**Number**: None
**XML Name**: iceProtection
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## preHeatingPreCooling
Description for preHeatingPreCooling.
### General Information
**Number**: None
**XML Name**: preHeatingPreCooling
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## sewageDisposalWaterSupply
Description for sewageDisposalWaterSupply.
### General Information
**Number**: None
**XML Name**: sewageDisposalWaterSupply
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## useOfMotorailFacilities
Description for useOfMotorailFacilities.
### General Information
**Number**: None
**XML Name**: useOfMotorailFacilities
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## longitude
Description for longitude.
### General Information
**Number**: None
**XML Name**: longitude
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## latitude
Description for latitude.
### General Information
**Number**: None
**XML Name**: latitude
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## crdPrimaryLocation
Description for crdPrimaryLocation.
### General Information
**Number**: None
**XML Name**: crdPrimaryLocation
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## crdSubsidiaryLocation
Description for crdSubsidiaryLocation.
### General Information
**Number**: None
**XML Name**: crdSubsidiaryLocation
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## rinfOperationalPoint
Description for rinfOperationalPoint.
### General Information
**Number**: None
**XML Name**: rinfOperationalPoint
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## facilityStreet
Description for facilityStreet.
### General Information
**Number**: None
**XML Name**: facilityStreet
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## facilityZip
Description for facilityZip.
### General Information
**Number**: None
**XML Name**: facilityZip
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## facilityTown
Description for facilityTown.
### General Information
**Number**: None
**XML Name**: facilityTown
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## facilityCountry
Description for facilityCountry.
### General Information
**Number**: None
**XML Name**: facilityCountry
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## connectionToPublicRailNetwork
Description for connectionToPublicRailNetwork.
### General Information
**Number**: None
**XML Name**: connectionToPublicRailNetwork
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## facilityLocatedOnRfc
Description for facilityLocatedOnRfc.
### General Information
**Number**: None
**XML Name**: facilityLocatedOnRfc
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## roadAccessConditions
Description for roadAccessConditions.
### General Information
**Number**: None
**XML Name**: roadAccessConditions
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## operationStatus
Description for operationStatus.
### General Information
**Number**: None
**XML Name**: operationStatus
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## openingTimes
Description for openingTimes.
### General Information
**Number**: None
**XML Name**: openingTimes
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## openOnDemand
Description for openOnDemand.
### General Information
**Number**: None
**XML Name**: openOnDemand
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## totalNumberOfTracks
Description for totalNumberOfTracks.
### General Information
**Number**: None
**XML Name**: totalNumberOfTracks
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## totalNumberOfPlatformTracks
Description for totalNumberOfPlatformTracks.
### General Information
**Number**: None
**XML Name**: totalNumberOfPlatformTracks
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## thereofElectrifiedPlatformTracks
Description for thereofElectrifiedPlatformTracks.
### General Information
**Number**: None
**XML Name**: thereofElectrifiedPlatformTracks
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## maxUsableLengthPlatformTracks
Description for maxUsableLengthPlatformTracks.
### General Information
**Number**: None
**XML Name**: maxUsableLengthPlatformTracks
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## totalNumberOfTranshipmentTracks
Description for totalNumberOfTranshipmentTracks.
### General Information
**Number**: None
**XML Name**: totalNumberOfTranshipmentTracks
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## thereofElectrifiedTranshipmentTracks
Description for thereofElectrifiedTranshipmentTracks.
### General Information
**Number**: None
**XML Name**: thereofElectrifiedTranshipmentTracks
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## maxUsableLengthTranshipmentTracks
Description for maxUsableLengthTranshipmentTracks.
### General Information
**Number**: None
**XML Name**: maxUsableLengthTranshipmentTracks
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## totalNumberOfStorageTracks
Description for totalNumberOfStorageTracks.
### General Information
**Number**: None
**XML Name**: totalNumberOfStorageTracks
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## thereofElectrifiedStorageTracks
Description for thereofElectrifiedStorageTracks.
### General Information
**Number**: None
**XML Name**: thereofElectrifiedStorageTracks
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## maxUsableLengthStorageTracks
Description for maxUsableLengthStorageTracks.
### General Information
**Number**: None
**XML Name**: maxUsableLengthStorageTracks
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## totalNumberOfShuntingTracks
Description for totalNumberOfShuntingTracks.
### General Information
**Number**: None
**XML Name**: totalNumberOfShuntingTracks
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## thereofElectrifiedShuntingTracks
Description for thereofElectrifiedShuntingTracks.
### General Information
**Number**: None
**XML Name**: thereofElectrifiedShuntingTracks
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## maxUsableLengthShuntingTracks
Description for maxUsableLengthShuntingTracks.
### General Information
**Number**: None
**XML Name**: maxUsableLengthShuntingTracks
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## totalNumberOfInboundOutboundTracks
Description for totalNumberOfInboundOutboundTracks.
### General Information
**Number**: None
**XML Name**: totalNumberOfInboundOutboundTracks
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## thereofElectrifiedInboundOutboundTracks
Description for thereofElectrifiedInboundOutboundTracks.
### General Information
**Number**: None
**XML Name**: thereofElectrifiedInboundOutboundTracks
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## maxUsableLengthInboundOutboundTracks
Description for maxUsableLengthInboundOutboundTracks.
### General Information
**Number**: None
**XML Name**: maxUsableLengthInboundOutboundTracks
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## totalNumberOfAllocationTracks
Description for totalNumberOfAllocationTracks.
### General Information
**Number**: None
**XML Name**: totalNumberOfAllocationTracks
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## thereofElectrifiedAllocationTracks
Description for thereofElectrifiedAllocationTracks.
### General Information
**Number**: None
**XML Name**: thereofElectrifiedAllocationTracks
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## maxUsableLengthAllocationTracks
Description for maxUsableLengthAllocationTracks.
### General Information
**Number**: None
**XML Name**: maxUsableLengthAllocationTracks
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## totalNumberOfOtherTracks
Description for totalNumberOfOtherTracks.
### General Information
**Number**: None
**XML Name**: totalNumberOfOtherTracks
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## thereofElectrifiedOtherTracks
Description for thereofElectrifiedOtherTracks.
### General Information
**Number**: None
**XML Name**: thereofElectrifiedOtherTracks
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## maxUsableLengthOtherTracks
Description for maxUsableLengthOtherTracks.
### General Information
**Number**: None
**XML Name**: maxUsableLengthOtherTracks
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## descriptionOfTechnicalCharacteristics
Description for descriptionOfTechnicalCharacteristics.
### General Information
**Number**: None
**XML Name**: descriptionOfTechnicalCharacteristics
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## technicalMap
Description for technicalMap.
### General Information
**Number**: None
**XML Name**: technicalMap
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## brakeTestFacility
Description for brakeTestFacility.
### General Information
**Number**: None
**XML Name**: brakeTestFacility
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## compressedAirSupply
Description for compressedAirSupply.
### General Information
**Number**: None
**XML Name**: compressedAirSupply
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## turntable
Description for turntable.
### General Information
**Number**: None
**XML Name**: turntable
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## locomotiveWashingCleaning
Description for locomotiveWashingCleaning.
### General Information
**Number**: None
**XML Name**: locomotiveWashingCleaning
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## wagonWashingCleaning
Description for wagonWashingCleaning.
### General Information
**Number**: None
**XML Name**: wagonWashingCleaning
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## loadingUnitWashingCleaning
Description for loadingUnitWashingCleaning.
### General Information
**Number**: None
**XML Name**: loadingUnitWashingCleaning
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## maintenanceShopLight
Description for maintenanceShopLight.
### General Information
**Number**: None
**XML Name**: maintenanceShopLight
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## maintenanceShopHeavy
Description for maintenanceShopHeavy.
### General Information
**Number**: None
**XML Name**: maintenanceShopHeavy
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## otherEquipment
Description for otherEquipment.
### General Information
**Number**: None
**XML Name**: otherEquipment
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## descriptionTechnicalEquipment
Description for descriptionTechnicalEquipment.
### General Information
**Number**: None
**XML Name**: descriptionTechnicalEquipment
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## numberOfGantryCranes
Description for numberOfGantryCranes.
### General Information
**Number**: None
**XML Name**: numberOfGantryCranes
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## numberOfMobileCranes
Description for numberOfMobileCranes.
### General Information
**Number**: None
**XML Name**: numberOfMobileCranes
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## horizontalTranshipmentSystems
Description for horizontalTranshipmentSystems.
### General Information
**Number**: None
**XML Name**: horizontalTranshipmentSystems
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## headRamp
Description for headRamp.
### General Information
**Number**: None
**XML Name**: headRamp
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## sideRamp
Description for sideRamp.
### General Information
**Number**: None
**XML Name**: sideRamp
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## loadingLane
Description for loadingLane.
### General Information
**Number**: None
**XML Name**: loadingLane
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## hump
Description for hump.
### General Information
**Number**: None
**XML Name**: hump
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## trackScale
Description for trackScale.
### General Information
**Number**: None
**XML Name**: trackScale
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## opticalCharacterRecognition
Description for opticalCharacterRecognition.
### General Information
**Number**: None
**XML Name**: opticalCharacterRecognition
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## numberOfReeferConnections
Description for numberOfReeferConnections.
### General Information
**Number**: None
**XML Name**: numberOfReeferConnections
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## storageAreaM2
Description for storageAreaM2.
### General Information
**Number**: None
**XML Name**: storageAreaM2
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## storageAreaTeu
Description for storageAreaTeu.
### General Information
**Number**: None
**XML Name**: storageAreaTeu
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## emptyContainerDepot
Description for emptyContainerDepot.
### General Information
**Number**: None
**XML Name**: emptyContainerDepot
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## numberOfPlatforms
Description for numberOfPlatforms.
### General Information
**Number**: None
**XML Name**: numberOfPlatforms
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## maxPlatformLength
Description for maxPlatformLength.
### General Information
**Number**: None
**XML Name**: maxPlatformLength
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## maxPlatformHeight
Description for maxPlatformHeight.
### General Information
**Number**: None
**XML Name**: maxPlatformHeight
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## minPlatformHeight
Description for minPlatformHeight.
### General Information
**Number**: None
**XML Name**: minPlatformHeight
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## escalatorRampForPlatformAccess
Description for escalatorRampForPlatformAccess.
### General Information
**Number**: None
**XML Name**: escalatorRampForPlatformAccess
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## weatherProtectionForPassengers
Description for weatherProtectionForPassengers.
### General Information
**Number**: None
**XML Name**: weatherProtectionForPassengers
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## plannedChangesTechnicalCharacteristics
Description for plannedChangesTechnicalCharacteristics.
### General Information
**Number**: None
**XML Name**: plannedChangesTechnicalCharacteristics
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## informationOnCharges
Description for informationOnCharges.
### General Information
**Number**: None
**XML Name**: informationOnCharges
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## informationOnDiscounts
Description for informationOnDiscounts.
### General Information
**Number**: None
**XML Name**: informationOnDiscounts
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## publicAccessibility
Description for publicAccessibility.
### General Information
**Number**: None
**XML Name**: publicAccessibility
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## legalRequirements
Description for legalRequirements.
### General Information
**Number**: None
**XML Name**: legalRequirements
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## electrifiedRailAccessPossible
Description for electrifiedRailAccessPossible.
### General Information
**Number**: None
**XML Name**: electrifiedRailAccessPossible
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## maxPermittedTrainLength
Description for maxPermittedTrainLength.
### General Information
**Number**: None
**XML Name**: maxPermittedTrainLength
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## maxPermittedAxleLoad
Description for maxPermittedAxleLoad.
### General Information
**Number**: None
**XML Name**: maxPermittedAxleLoad
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## minTrackRadius
Description for minTrackRadius.
### General Information
**Number**: None
**XML Name**: minTrackRadius
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## clearanceGauge
Description for clearanceGauge.
### General Information
**Number**: None
**XML Name**: clearanceGauge
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## lengthOfAccessBranchLine
Description for lengthOfAccessBranchLine.
### General Information
**Number**: None
**XML Name**: lengthOfAccessBranchLine
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## accessLineElectrification
Description for accessLineElectrification.
### General Information
**Number**: None
**XML Name**: accessLineElectrification
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## accessLineMaxPermittedTrainLength
Description for accessLineMaxPermittedTrainLength.
### General Information
**Number**: None
**XML Name**: accessLineMaxPermittedTrainLength
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## accessLineMaxAxleLoad
Description for accessLineMaxAxleLoad.
### General Information
**Number**: None
**XML Name**: accessLineMaxAxleLoad
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## accessLineMinTrackRadius
Description for accessLineMinTrackRadius.
### General Information
**Number**: None
**XML Name**: accessLineMinTrackRadius
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## accessLineClearanceGauge
Description for accessLineClearanceGauge.
### General Information
**Number**: None
**XML Name**: accessLineClearanceGauge
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## accessLineMaxIncline
Description for accessLineMaxIncline.
### General Information
**Number**: None
**XML Name**: accessLineMaxIncline
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## containerAcceptance
Description for containerAcceptance.
### General Information
**Number**: None
**XML Name**: containerAcceptance
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## containerSizeLimit
Description for containerSizeLimit.
### General Information
**Number**: None
**XML Name**: containerSizeLimit
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## containerWeightLimit
Description for containerWeightLimit.
### General Information
**Number**: None
**XML Name**: containerWeightLimit
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## swapBodyAcceptance
Description for swapBodyAcceptance.
### General Information
**Number**: None
**XML Name**: swapBodyAcceptance
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## swapBodySizeLimit
Description for swapBodySizeLimit.
### General Information
**Number**: None
**XML Name**: swapBodySizeLimit
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## swapBodyWeightLimit
Description for swapBodyWeightLimit.
### General Information
**Number**: None
**XML Name**: swapBodyWeightLimit
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## trailerAcceptance
Description for trailerAcceptance.
### General Information
**Number**: None
**XML Name**: trailerAcceptance
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## trailerSizeLimit
Description for trailerSizeLimit.
### General Information
**Number**: None
**XML Name**: trailerSizeLimit
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## trailerWeightLimit
Description for trailerWeightLimit.
### General Information
**Number**: None
**XML Name**: trailerWeightLimit
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## truckTrailerAcceptance
Description for truckTrailerAcceptance.
### General Information
**Number**: None
**XML Name**: truckTrailerAcceptance
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## conventionalCargoAcceptance
Description for conventionalCargoAcceptance.
### General Information
**Number**: None
**XML Name**: conventionalCargoAcceptance
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## palletisedGoods
Description for palletisedGoods.
### General Information
**Number**: None
**XML Name**: palletisedGoods
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## bulk
Description for bulk.
### General Information
**Number**: None
**XML Name**: bulk
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## fluidsAndGas
Description for fluidsAndGas.
### General Information
**Number**: None
**XML Name**: fluidsAndGas
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## dangerousGoods
Description for dangerousGoods.
### General Information
**Number**: None
**XML Name**: dangerousGoods
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## ridClasses
Description for ridClasses.
### General Information
**Number**: None
**XML Name**: ridClasses
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## wood
Description for wood.
### General Information
**Number**: None
**XML Name**: wood
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## heavyLoads
Description for heavyLoads.
### General Information
**Number**: None
**XML Name**: heavyLoads
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## reeferCargo
Description for reeferCargo.
### General Information
**Number**: None
**XML Name**: reeferCargo
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## otherCargoTypes
Description for otherCargoTypes.
### General Information
**Number**: None
**XML Name**: otherCargoTypes
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## selfSupplyOfRailRelatedServices
Description for selfSupplyOfRailRelatedServices.
### General Information
**Number**: None
**XML Name**: selfSupplyOfRailRelatedServices
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## itSystems
Description for itSystems.
### General Information
**Number**: None
**XML Name**: itSystems
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## requestsForAccessOrServices
Description for requestsForAccessOrServices.
### General Information
**Number**: None
**XML Name**: requestsForAccessOrServices
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## bookingConditions
Description for bookingConditions.
### General Information
**Number**: None
**XML Name**: bookingConditions
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## responseToRequests
Description for responseToRequests.
### General Information
**Number**: None
**XML Name**: responseToRequests
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## availableCapacity
Description for availableCapacity.
### General Information
**Number**: None
**XML Name**: availableCapacity
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## temporaryCapacityRestrictions
Description for temporaryCapacityRestrictions.
### General Information
**Number**: None
**XML Name**: temporaryCapacityRestrictions
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## cooperationBetweenSfAndIm
Description for cooperationBetweenSfAndIm.
### General Information
**Number**: None
**XML Name**: cooperationBetweenSfAndIm
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------

## statusChange
Description for statusChange.
### General Information
**Number**: None
**XML Name**: statusChange
**Deadline**: None

### Data Format
* **Data Presentation**
None
* **Taxonomy Reference**
None

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
None

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------
