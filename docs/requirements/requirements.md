# System Requirements

## Functional requirements

* **FR1:** The system shall allow authenticated users to shorten a valid URL
into a unique, 6 character long shortened URL.
* **FR2:** The system shall allow only authorized personnel to make an account.
* **FR3:** The system shall redirect users from shortened URLs to the full URL.
* **FR4:** The system shall log the date and time of each click to each URL
* **FR5:** The system shall allow users to set an expiration date, with a
default of 1 year.
* **FR6:** The system shall keep the logs of a created link for 2 years after
its creation.
* **FR7:** The system shall allow the owner of a URL and administrators to
delete that URL.

## Non Functional Requirements

* **NFR1:** The system shall be able to serve 50 redirects per second and 10
link creations per second while responding in < 200ms.
* **NFR2:** The system shall encrypt all traffic in HTTPS and not store
sensitive data as plain text.
* **NFR3** The system's binary shall be able to handle 10,000 concurrent
connections using < 2 GB of RAM.
* **NFR4:** The system's database shall be able to store 100,000 links and
20,000,000 logs without exceeding 32 GB of disk.

## Constraints

* **SC1:** The system shall run on a machine running Fedora Linux 43 with 4GB of
RAM and 64GB of disk.
* **SC2:** There shall be a usable prototype of the system in 6 weeks for
stakeholders to see.
