
# Proposed Parameters from NS to be added to ERA Ontology/RINF

## Problem settin

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

**Type:** [Double](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23double) 

**Description:** Maximum permitted axle load, given in tons.

**Regulation:** UIC leaflet 700-0

## Maximum Meter load
**Has domain:** [Section of Line](http://data.europa.eu/949/SectionOfLine)

**Type:** [Double](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23double)

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

## Noise level
**Has domain:** [Section of Line](http://data.europa.eu/949/SectionOfLine)

**Type:** [Boolean](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23boolean)

**Description:** Indicate, if there are any limits on noise levels.

**Regulation:** n/a

## Restricted classes of dangerous goods
**Has domain:** [Section of Line](http://data.europa.eu/949/SectionOfLine)

**Type:** [Boolean](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23boolean)

**Description:** Indicate, if there are any limits on specific type of dangerous goods.

**Regulation:** n/a

## Restricted times of the day for transport of dangerous goods
**Has domain:** [Section of Line](http://data.europa.eu/949/SectionOfLine)

**Type:** [Boolean](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23boolean)

**Description:** Indicate, if there are any limits on specific time of a day for transport of dangerous goods.

**Regulation:** n/a

## Opening hours
**Has domain:** [Section of Line](http://data.europa.eu/949/SectionOfLine)

**Type:** [Boolean](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23boolean)

**Description:** Indicate, if there are any opening hours of the section of a line.

**Regulation:** n/a

## Tunnel speed limit
**Has domain:** [Tunnel](http://data.europa.eu/949/Tunnel)

**Type:** [Integer](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23integer)

**Description:** Indicate the speed limit in a tunnel.

**Regulation:** n/a

## Restricted type of vehicle
**Has domain:** [Tunnel](http://data.europa.eu/949/Tunnel)

**Type:** [Boolean](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23boolean)

**Description:** Indicate, if there are any limits on specific type of vehicle.

**Regulation:** n/a

## Exclusion of simultaneity
**Has domain:** [Tunnel](http://data.europa.eu/949/Tunnel)

**Type:** [Boolean](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23boolean)

**Description:** Indicate, if passenger and freight trains meeting together in a tunnel is allowed.

**Regulation:** n/a

## Transportation of dangerous goods
**Has domain:** [Tunnel](http://data.europa.eu/949/Tunnel)

**Type:** [Boolean](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23boolean)

**Description:** Indicate, if there are any limits on transportation of dangerous goods.

**Regulation:** n/a

## Tunnel opening hours
**Has domain:** [Tunnel](http://data.europa.eu/949/Tunnel)

**Type:** [Boolean](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23boolean)'

**Description:** Indicate, if there are any opening hours of the tunnel.

**Regulation:** n/a

## Bridge wind restriction
**Has domain:** [Track](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fdata.europa.eu%2F949%2FTrack)

**Type:** [Boolean](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23boolean)

**Description:** Indicate, if there are any wind restrictions for a bridge.

**Regulation:** n/a

## Bridge opening hours
**Has domain:** [Track](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fdata.europa.eu%2F949%2FTrack)

**Type:** [Boolean](https://data-interop.era.europa.eu/describe#http%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23boolean)

**Description:** Indicate, if there are any opening hours of the bridge.

**Regulation:** n/a
