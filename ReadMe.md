# A Possible Approach For Building Micro Services Using Apache Camel.

## Example Use Case
Acme bank wants to modernize it's credit application portfolio using a micro services based architecture.
The example is organized along the following lines.

* Each individual credit product (Ex creditcard, Loan, HELOC, Mortgage) is built as a separate service.

* Common business logic will be built as services. (Ex Customer profile retrieval, Credit Bureau verification, Adjudication submition).

* Each Service will be exposed via a REST or JMS interface.
