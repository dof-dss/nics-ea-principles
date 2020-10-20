## 5. Adhere to functional domains

### Description

The business rules and functionality of a system are consistent with the mission of
that application. There is complete adherence to the functional domain in which the
application is located.

### Rationale

The purpose of this principle is to avoid functional redundancy between applications. Functional redundancy can cause loss of data integrity and increase maintenance costs related to the redundant business rule.

There should be good cause for introducing anything into the NICS IT landscape. There must be a well understood reason - a specific user need or problem being addressed, or an opportunity being exploited -for introducing the asset. It follows therefore that everything must be adding value to someone, and the outcome of introducing the asset - some change in user behaviour must be measurable. It is imperative that a metric that truly measures the asset’s reason for existing be identified and a mechanism for gathering the metric be implemented.

### Implications

- Applications must be located in proper functional domains, with explicit definition of the manager in charge of the functional domain.
- Each new functionality request must be submitted to the respective manager.
- Applications that are already in production with functional redundancy should be replaced entirely or partially in a timely manner. The functional redundancy of such applications must not be promoted.
- There must be a tangible reason why work is being undertaken and who will benefit from it, i.e. the desired outcome the work is intended to achieve.
- Develop knowledge of your target audience (who) and what that means for your work.
- One “metric that matters” / Key Performance Indicator (KPI) should be identified that truly reflects
whether the desired outcome is being achieved or not.
- The KPI must be actionable and give some context, i.e. a ratio or percentage. For example, a KPI reporting “300 transactions completed online last month” doesn’t have the context to understand if 300 was good or not. A KPI reporting 60% (or 6%) gives meaning and context that can be used to better inform decision making around next steps.
- Steps must be taken to collect necessary data to report on the KPI as part of the first deliverable, in order to create a feedback loop.
- A hypothesis-based approach, where assumptions are de-risked to build confidence should be adopted.
  A suggested format is as follows:
  - We believe *introducing a shiny new asset (what)*
  - Will *bring about a positive change (why)*
  - For *users (who)*
  - We will know this is true when *we achieve target% change in users’ behaviour (KPI)*

  The hypothesis should then be tested to determine if the assumed “cause and effect” relationship actually exists, and if that correlation is sufficiently strong. A threshold for determining if the hypothesis is valid or not is declared up front. For example:

- We believe caching database calls
- Will make our web page appear faster and more responsive
- For citizens applying for a required permit
- We will know this is true when we see page load times improve by 20%
