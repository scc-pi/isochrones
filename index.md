Creating Isochrones Notes
================

## Introduction

Planning are drafting policy to restrict new takeaways in certain areas.
One of the criteria is no new takeaways within 400m of secondary
schools. Current adopted policies use buffers, i.e. as-the-crow-flies,
for such measurements. However, a more accurate measurement would be a
400m walk. For these we use isochrones. Strictly speaking a 400m
distance from a school is an isodistance and a 5 minute walk is an
isochrone, but the term isochrone is generally used to cover both
distance and time from a point. The diagrams below illustrate the
difference between a buffer and an isochrone:

*TODO: resize .pngs and caption*

<img src="Images/buffer.png" title="circle" alt="Buffer" width="300"/>

<img src="Images/isochrone.png" title="irregular polygon" alt="Isochrone" width="300"/>

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
(requires a license and login credentials) created to help draft for the
takeaways policy.

# Appendix

## ToDo

-   Left column navigation

-   Separate documents

## GitHub Documents

This is an R Markdown format used for publishing markdown documents to
GitHub. When you click the **Knit** button all R code chunks are run and
a markdown file (.md) suitable for publishing to GitHub is generated.

Unlike the [Notes](https://scc-pi.github.io/notes/) site, the bulk of
the rendering is done locally rather than via GitHub Actions. To some
extent this is simpler, and it also works around where rendering needing
to reference a local licensed installation of ArcGIS desktop. The site
is setup as per the basic [GitHub Pages
guidance](https://guides.github.com/features/pages). The rendering that
isn’t local is via a [Jekyll
theme](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll).
