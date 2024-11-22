
# Proposed Parameters from NS to be added to ERA Ontology/RINF

## Problem setting

As part of RNE’s work supporting the IMs digitalising their network statement, RNE has been contracted to study, define and propose additional infrastructure parameters which would be needed for RINF to effectively cover the nature of the infrastructure part of the network statement. After comparision between the parameters of the Network Statement Common Structure with those of the RINF Register of Infrastructure and ERA Vocabulary, RNE proposed the following parameters to enrich ERA Ontology and as inputs for future developments of the RINF application.

## Proposed solution


## Connecting Infrastructure Manager
**Has domain:** [Section of Line](http://data.europa.eu/949/SectionOfLine)

**Type:** 'xsd:boolean'

**Description:** Indicates whether any neighbouring section of line belongs to different Infrastructure Manager

**Regulation:** n/a

## Loading Gauge
**Has domain:** [Section of Line](http://data.europa.eu/949/SectionOfLine)

**Type:** [Integer](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23double)

**Description:** Maximum physical dimensions (height and width) to which an open rail wagon can be loaded.

**Regulation:** EN 15273 / Combined Traffic Codes

## Maximum Axle load
**Has domain:** [Section of Line](http://data.europa.eu/949/SectionOfLine)

**Type:** [Tons](https://qudt.org/vocab/unit/TONNE)

**Description:** Maximum permitted axle load, given in tons.

**Regulation:** UIC leaflet 700-0

## Maximum Meter load
**Has domain:** [Section of Line](http://data.europa.eu/949/SectionOfLine)

**Type:** [Tons](https://qudt.org/vocab/unit/TONNE)

**Description:** Maximum permitted meter load, given in tons.

**Regulation:** UIC leaflet 700-0

## Maximum Train Length
**Has domain:** [Section of Line](http://data.europa.eu/949/SectionOfLine)

**Type:** [Integer](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23integer)

**Description:** Maximum train length allowed on a line or section.

**Regulation:** n/a

## Specialized Infrastructure
**Has domain:** [Section of Line](http://data.europa.eu/949/SectionOfLine)

**Type:** [String](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23anyURI)

**Description:** Special type of service on a line or a section of a line.

**Regulation:** n/a

## Noise level limits
**Has domain:** [Section of Line](http://data.europa.eu/949/SectionOfLine)

**Type:** [Boolean](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23boolean)

**Description:** Indicate, if there are any limits on noise levels.

**Regulation:** n/a

**If True:** 

### &nbsp;&nbsp;&nbsp;&nbsp; Noise level

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:** [dB](https://qudt.org/vocab/unit/DeciB)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;***Description:*** Maximum allowed noise level in decibels (dB).


## Existence of restricted dangerous goods 
**Has domain:** [Tunnel](http://data.europa.eu/949/Tunnel) / [Section of Line](http://data.europa.eu/949/SectionOfLine)

**Type:** [Boolean](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23boolean)

**Description:** Indicate, if there are any limits on transportation of dangerous goods.

**Regulation:** n/a

**If True:** 

### &nbsp;&nbsp;&nbsp;&nbsp; Restricted dangerous goods

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**  [String](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23anyURI)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;***Description:*** Description of the type of dangerous good that are not allowed in the tunnel

## Existence of restricted periods of time for dangerous goods transportation
**Has domain:** [Section of Line](http://data.europa.eu/949/SectionOfLine)

**Type:** [Boolean](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23boolean)

**Description:** Indicate, if there are any limits on specific time of a day for transport of dangerous goods.

**Regulation:** n/a

**If True:** 

### &nbsp;&nbsp;&nbsp;&nbsp; Period of time

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**  [String](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23anyURI)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;***Description:*** Describes the period of time for which the transport of dangerous goods is not allowed in the Section of Line


## Existence of opening hours limitation
**Has domain:** [Section of Line](http://data.europa.eu/949/SectionOfLine)

**Type:** [Boolean](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23boolean)

**Description:** Indicate, if there are any opening hours of the section of a line.

**Regulation:** n/a

**If True:** 

### &nbsp;&nbsp;&nbsp;&nbsp; Opening hours

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**  [String](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23anyURI)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;***Description:*** Opening hours of the class.

## Tunnel speed limit
**Has domain:** [Tunnel](http://data.europa.eu/949/Tunnel)

**Type:** [Km/h](http://qudt.org/vocab/unit/KiloM-PER-HR)

**Description:** Indicate the speed limit in a tunnel.

**Regulation:** n/a

## Existence of restricted type of vehicle
**Has domain:** [Tunnel](http://data.europa.eu/949/Tunnel)

**Type:** [Boolean](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23boolean)

**Description:** Indicate, if there are any limits on specific type of vehicle.

**Regulation:** n/a

**If True:** 

### &nbsp;&nbsp;&nbsp;&nbsp; Restricted type of vehicle

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**  [String](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23anyURI)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;***Description:*** Description of the type vehicles that cannot use the tunnel.

## Exclusion of simultaneity
**Has domain:** [Tunnel](http://data.europa.eu/949/Tunnel)

**Type:** [Boolean](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23boolean)

**Description:** Indicate, if passenger and freight trains meeting together in a tunnel is allowed.

**Regulation:** n/a


## Tunnel opening hours limitation
**Has domain:** [Tunnel](http://data.europa.eu/949/Tunnel)

**Type:** [Boolean](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23boolean)'

**Description:** Indicate, if there are any opening hours of the tunnel.

**Regulation:** n/a

**If True:** 

### &nbsp;&nbsp;&nbsp;&nbsp; Opening hours

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**  [String](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23anyURI)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;***Description:*** Opening hours of the class.

## Bridge wind restriction
**Has domain:** [Track](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fdata.europa.eu%2F949%2FTrack) /
    [Bridge](https://linkedvocabs.org/data/era-ontology/3.1.0/doc/index-en.html#Bridge)  ERA Ontology 3.1.0

**Type:** [Boolean](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23boolean)
      

**Description:** Indicate, if there are any wind restrictions for a bridge.

**Regulation:** n/a

**If True:** 

### &nbsp;&nbsp;&nbsp;&nbsp; Maximun wind

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**  [Km/h](http://qudt.org/vocab/unit/KiloM-PER-HR)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;***Description:*** Indicates the maximun wind speed for which the bridge can operate

## Bridge opening hours limitation
**Has domain:** [Track](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fdata.europa.eu%2F949%2FTrack) /
                [Bridge](https://linkedvocabs.org/data/era-ontology/3.1.0/doc/index-en.html#Bridge)  ERA Ontology 3.1.0

**Type:** [Boolean](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23boolean)

**Description:** Indicate, if there are any opening hours of the bridge.

**Regulation:** n/a

**If True:** 

### &nbsp;&nbsp;&nbsp;&nbsp; Opening hours

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Type:**  [String](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23anyURI)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;***Description:*** Opening hours of the class.
