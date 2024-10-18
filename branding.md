# Concept

The branding concept has been developed in a paper by Taylor et al. with the aim, among others, of promoting greater clarity and scalability in the naming of variables used in WCRP model intercompaison projects (MIPs).

## Taylor et al.

Taylor et al. propose an approach in which the brand is defined in terms of four short labels:

* TemporalLabelDD
* VerticalLabelDD
* HorizontalLabelDD
* AreaLabelDD

## Data Request Vocabularies

An alternative proposal is based more directly on vocabularies in the current request:

* Spatial Shape
* z-axis Coordinates
* Cell Methods

## Implementation

Both are implemented in the AR7 Fast Track Data Request, and can be seen in the [working copy of the data request](https://airtable.com/appBWxP0SS7K1hweJ/shrxhV6tenQBnOGRj), with the Taylor et al. approach labelled "Brand (WIP)" and the alternative labelled "Brand (DR)". 

The "Brand (WIP)" approach produces 125 different values (including several for metadata combinations which are incomplete at this stage); the "Brand (DR)" approach has 164 different values. In some cases there is a one-to-one correspondence: e.g. "tavg-l-hxy-sea" matches "tmn-ol-hxy-amns" exactly. In other cases the WIP version maps onto multiple DR versions.

The key advantage of the DR version is that each "brand" corresponds to a unique combination of cell methods, spatial amd temporal dimensions. This gives it greater simplicity in implementation and greater utility:




