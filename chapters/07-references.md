# References & Tech stack choices

This chapter provide the choosen technology stack as referred to goals and constraints in chapter 1. There are few main factor of technology stack to choose:

* Open source, the choosen stack should have open source license to avoid vendor lock.
* Documentation, the choosen stack should provide comprehensive documentation, and actively maintenaned.
* Reliability, the choosen stack should already have real production running proven.
* Developer resources, the choosen stack should already widely used by developers by using github report indicator.
* Easy to scale, the choosen stack should be able to accomodate horizontal scaling without major rewrite or refactor.

## Programming Languages

### Javascript

Javascript has been widely used for multiple platform from frontend to backend using NodeJS. Using javascript to develop the system will be logical reason to faster development. The streaming features for video/audio conferences also makes perfect fit for NodeJS non-blocking features.

## Databases

* MongoDB. it's NoSQL document based database will be fit for current architecture as it support high concurency writes.
* Redis. Redis will act as cache database to improve latency. Any write/update query will be queue to the main database using pub/sub method.

## Frameworks

* NodeJS. NodeJS will be used for all backend related services
* Typesense. Typesense will be used for search features from any services requiring full text search index.

## CI/CD

Since all codebase will be hosted in Github, using Github Action will be fit into the situation

## Mobile Application

Using hybrid mobile app framework such Flutter or React Native for faster development
