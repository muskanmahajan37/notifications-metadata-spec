# Notifications Spec

## About

This repository aims to standardize API components to publish and subscribe to geospatial notificiations. A number of software and data providers have been creating RESTful JSON-based image catalogs, and geospatial systems. These end up all looking fairly similar, but are still different enough that each needs custom-coded client libraries. A set of standardized API's
should increase interoperability, enabling more M2M and IoT interoperability.

## Contributing

Anyone building software that uses notifications with a geospatial context is welcome to collaborate. Our goal is to be a collaboration of developers, not [architecture astronauts](http://www.joelonsoftware.com/articles/fog0000000018.html).
The first step to join the collaboration is to add a folder to the 'implementations' folder with an [OpenAPI Spec](https://github.com/OAI/OpenAPI-Specification/blob/master/versions/2.0.md) (v2.0) of your implementation,
along with markdown document describing your implementation.

The developers of this repository will create specs to progress towards a common cloud-centric standard. From there
the spec(s) will evolve according to open source principles, using github as the primary tooling (pull requests and reviews for all changes, etc).


## In this repo

This repository contains the core [Principles](principles.md) that govern the collaboration.
The [implementations/](implementations) folder is where existing catalog implementations are detailed,
and is the center of the first part of collaboration. There is also a [Design Discussion](design-discuss.md)
on some of the bigger questions.

Once a number of implementations are evaluated work will begin on draft specification.
