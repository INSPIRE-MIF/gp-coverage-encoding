# Good Practice: OGC compliant INSPIRE coverage data and service implementation

This repository contains a specification for setting up INSPIRE coverage data and services aligned with OGC specifications.

[Coverage](https://en.wikipedia.org/wiki/Coverage_data) data provide a unified way to describe spatio-temporal regular and irregular grids, point clouds, and general meshes.
INSPIRE currently relies on the OGC Coverage Implementation Schema (CIS).

INSPIRE coverage services rely on 
- OGC Web Coverage Service (WCS) Core: basic services for coverage download, extraction, and encoding (mandatory in INSPIRE)
- OGC Web Coverage Processing Service (WCPS): datacube processing service for any kind of extraction, reprojection, aggregation, analytics, fusion, visualization of grid coverages (optional in INSPIRE)

A [primer on OGC coverages](https://earthserver.eu/wcs), together with links to manifold slide decks, webinars, and documentation is provided by [EarthServer](https://earthserver.eu). Further, WCS and WCPS are illustrated in a spectrum of functionalities, clients, and across dimensions in the [Earth Datacube Playground](https://standards.rasdaman.com/).

The  publicly available [INSPIRE Coverages Candidate Good Practice service](https://inspire-wcs.eu), based on rasdaman, showcases coverage types across various INSPIRE Annexes, including processing and fusion with both WCS and WCPS. It has been presented to the public in an [INSPIRE webinar held in February 2021](https://inspire.ec.europa.eu/coverage-good-practice).

A short note that we've now solved all problems with validating rasdaman WCS, details at: https://www.geoconnexion.com/news/rasdaman-validated-as-inspire-compliant-wcs
