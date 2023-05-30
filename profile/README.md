# Coursum
An alternative course summary system for SFC student. (no longer maintained)

## Main Projects

### [coursum-types](https://github.com/coursum/coursum-types/)
Shared TypeScript definitions for Coursum projects.

### [scrape-syllabus-data](https://github.com/coursum/scrape-syllabus-data)
CLI program for scraping course data from https://syllabus.sfc.keio.ac.jp

### [coursum-backend](https://github.com/coursum/coursum-backend)
A server that provide API to search course data.

### [coursum-frontend](https://github.com/coursum/coursum-frontend)
The coursum frontend client that use Course Schema V2.

## Other Projects
### [coursum-benchmark](https://github.com/coursum/coursum-benchmark)
A benchmark project that compared the speed of request between Coursum and the current syllabus system.

### [coursum-backend-golang](https://github.com/coursum/coursum-backend-golang)
The backend server that is seperated from [sfc-course-guide](https://github.com/coursum/sfc-course-guide). \
Its course data type should match with Course Schema V1.

| Branch | Data Source                  |
| ------ | ---------------------------- |
| SOL    | SOL database                 |
| master | scrape from previouse system |

### [sfc-course-guide](https://github.com/coursum/sfc-course-guide)
The first version of coursum system.
