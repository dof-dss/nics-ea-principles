## 4. Implement service based interfaces

### Description

Define interfaces that have low coupling, are self-described, and offer low impact on the
design of solutions as a result of changes. All data stores must be exposed via APIs.

All applications must provide APIs and/or message queues as standard to maximise reuse
and interoperability.

### Rationale

Low-coupling interfaces are preferable, because when interfaces between independent applications are highly coupled, they are less generic and more susceptible to causing unwanted, secondary effects when they are changed.

### Implications

- Low coupling means that the services (e.g. API’s) are designed and built with no affinity to a certain serviceconsumer.
- Therefore, the service is completely uncoupled from the service consumer. However, the service consumer is dependent of the service (that is, contains references for service-based interfaces).
- The service is also responsible for exception treatment. The result is a low-coupling architecture.
- When building systems or new services, expose any functionality via APIs or queues and communicate
with other services using message queues (where possible) or API calls (where sync exchange of data is
required).
- Guidance in the form of an API Style Guide must be published to ensure quality and standardisation of APIs.
- An enterprise service bus is required to support message transportation around the enterprise.
- Common vocabulary and data definitions must be defined to ensure interoperability between systems.
