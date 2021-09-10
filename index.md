---
nav_order: 1
---

Introduction
================

As part of helping to draft a new policy we need to consider areas
within 400m of secondary schools. Buffers have previously been used for
such measurements i.e. as-the-crow-flies. However, for the draft policy
a more accurate measurement would be a 400m walk and using isochrones.
The diagrams below illustrate the difference between a buffer and an
isochrone:

*TODO: resize .pngs and caption*

<img src="Images/buffer.png" title="circle" alt="Buffer" width="300"/>

<img src="Images/isochrone.png" title="irregular polygon" alt="Isochrone" width="300"/>

Strictly speaking, a 400m distance from a school is an isodistance and a
5 minute walk is an isochrone. However, the term isochrone is generally
used to cover both distance and time from a point.

The purpose of these notes is to understand:

1.  The best network dataset/service and software to use to create the
    isochrones.

2.  How to define the school points e.g. the main school entrance?

The best network dataset/service and software to use will be looked at
in descending order of convenience i.e. those further down the list
require more effort:

-   AGOL logistic service and ArcGIS Pro

-   openrouteservice and R

-   OS MasterMap Highways Network and Portal

-   OS MasterMap Highways Network and ArcGIS Pro

The resulting isochrones will be included in the [Portal
App](https://sheffieldcitycouncil.cloud.esriuk.com/portal/apps/View/index.html?appid=ba3cbfdb0c3642c6bfe48500b11473e9)
(requires a license and login credentials), which was created to help
draft the policy.
