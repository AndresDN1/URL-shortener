# Glossary

This document describes the Domain Specific Language used for the development of
the system, using a Domain Driven Development approach.

| Term | Definition | Category |
| :--- | :--- | :--- |
|Administrator |Person with privileged permissons in the system|Actor/Entity|
|Click|The event of a visitor clicking a link| Event|
|Expiration Time| Time at which a link or log can be removed| Value Object|
|Link|The map of short to long URLs and their logs| Entity/Aggregate|
|Log|The information stored about the link when a click happens| Value Object|
|Long URL | The full URL to be shortened| Value Object|
|Retention Worker|The system actor that cleans up links and logs passed their expiration time| Service|
|Short URL|The shortened version of the long URL| Value Object|
|Staff| The person from the company that creates the link|Actor/Entity|
|Visitor|The person who visits the link| Actor|
