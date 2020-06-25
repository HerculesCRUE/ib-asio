![](./images/logos_feder.png)

# ASIO: a Research Management System based on Semantic technologies

The [ASIO](https://www.um.es/web/hercules/proyectos/asio) project provides the architecture of a Research Management System based on Semantic technologies. The system is composed from two main modules: ontological infrastructure and research management system which are communicated through an RDF triple store that integrates all the information. The data model is defined in terms of Shape Expressions which are synchronized with Java entities that define the data model. 

The shapes also act as core layer that can be used to describe the main entities that will be employed and to validate their ontological definitions with test data. In this way, we propose a test-driven development approach for ontological engineering that improves the quality of both the ontologies defined and the data. The semantic architecture is based on a reactive approach which combines both a clean architecture and a stream-based pattern. 

This project is part of [HÉRCULES Semantic University Research Data Project](https://www.um.es/web/hercules/), which is backed by the Ministry of Economy, Industry and Competitiveness with a budget of 5.462.600,00 euros with an 80% of co-financing from the 2014-2020 ERDF Program. Hercules initiative is part also of [CRUE-TIC](http://www.crue.org/SitePages/ProyectoHercules.aspx).

## Video and screenshots

A demonstration video can be accessed on this link:

[https://github.com/HerculesCRUE/ib-asio/blob/master/HERCULES_ASIO_CIKM_video.mkv](https://github.com/HerculesCRUE/ib-asio/blob/master/HERCULES_ASIO_CIKM_video.mkv)

Additionally, a PDF with a brief explanation of the project and screenshots can be also accessed on this link:

[https://github.com/HerculesCRUE/ib-asio/blob/master/HERCULES_ASIO_CIKM_screenshots.pdf](https://github.com/HerculesCRUE/ib-asio/blob/master/HERCULES_ASIO_CIKM_screenshots.pdf)

## Related GitHub repositories

The project is subdivided in several functional modules plus documentation repositories:

- [ib-asio-abstractions](https://github.com/HerculesCRUE/ib-asio-abstractions): common resources for all modules (classes, constants, etc)
- [ib-domain-model](https://github.com/HerculesCRUE/ib-domain-model): general backend domain model
- [ib-dataset-domain-model](https://github.com/HerculesCRUE/ib-dataset-domain-model): domain model for sample dataset from University of Murcia
- [ib-event-processor](https://github.com/HerculesCRUE/ib-event-processor): input event processor module for Kafka streams
- [ib-management-system](https://github.com/HerculesCRUE/ib-management-system): data management system for input processor
- [ib-triples-storage-adapter](https://github.com/HerculesCRUE/ib-triples-storage-adapter): storage adapter for storing data in triple store
- [ib-uris-generator](https://github.com/HerculesCRUE/ib-uris-generator): library module for generation and management of persistent URIs