Version: NAFATH-V2
Track: Data

## Overview
A reliable 5G service for emergency responders depends on six IT fields working together. Software connects users to network services and allows different systems to communicate. Artificial intelligence (AI) helps analyse network data and predict problems such as congestion. Mobile applications give responders access to important information, including some features that work offline. Networking supports the 5G infrastructure and manages traffic when demand is high. Cybersecurity protects systems and sensitive information from attacks. Data engineering collects and organises network measurements so teams can monitor performance and prepare accurate reports. Each field supports the others. For example, organised data helps AI make better predictions, while cybersecurity protects the information used by applications. Networking helps maintain connectivity, and software brings services together. Cooperation between these six fields helps provide a dependable 5G service when emergency responders need it most.
## Software
HTTP methods describe the actions a client requests from a server. A safe method, such as GET, is intended to read information without requesting a change to the resource. An idempotent method has the same intended effect when the same request is repeated. PUT and DELETE are idempotent, although they have different purposes. These properties help developers design APIs and decide when a failed request can safely be retried.

Resource: RFC 9110: HTTP Semantics - https://www.rfc-editor.org/rfc/rfc9110.html
## AI
Overfitting happens when a machine learning model performs well on training data but poorly on new examples. One way to identify this problem is to compare training and validation performance. Data is commonly divided into training, validation, and test sets. The validation set helps developers compare models and adjust settings, while the test set provides a final evaluation. Cross-validation can also help estimate model performance by evaluating it across different data splits.

Resource: Datasets: Dividing the original dataset - https://developers.google.com/machine-learning/crash-course/overfitting/dividing-datasets
## Mobile
An offline-first mobile application can perform its main tasks without a reliable internet connection. It stores important information locally so users can still access it when connectivity is lost. When the connection returns, the application can update data between local and remote sources. Developers must consider failed requests, data conflicts, and synchronization rules. These decisions are important for emergency responders who may need critical information in areas with weak network coverage.
Resource: Build an offline-first app - https://developer.android.com/topic/architecture/data-layer/offline-first
## Networking
5G network slicing allows a mobile operator to create separate logical networks on shared network infrastructure. Each slice can be designed for the needs of a particular service or group of users. For example, emergency responders may need reliable communication, while other services may focus on high data speeds. Network slicing helps operators manage different requirements, but its effectiveness depends on correct configuration, resource management, and security.

Resource: 3GPP - 5G System Architecture and Network Slicing - https://www.3gpp.org/ftp/inbox/marcoms/ICT_6_1-2.pdf
## Cybersecurity
Incident response is the process an organisation follows when a cybersecurity incident occurs. Teams prepare before incidents happen, monitor systems to detect suspicious activity, and analyse evidence to understand the problem. They then contain the incident to limit its impact, remove the threat, and recover affected systems. Afterward, they review what happened and identify improvements. Clear responsibilities and communication help teams respond effectively and reduce disruption.

Resource: NIST - Incident Response - https://csrc.nist.gov/projects/incident-response
## Data
A star schema organises analytical data around a central fact table connected directly to dimension tables. A snowflake schema extends this design by splitting some dimension tables into related, more normalised tables. Star schemas are often easier to understand and may require fewer joins in queries. Snowflake schemas can reduce duplicated descriptive data but may need more joins. The appropriate design depends on reporting needs, data structure, and performance requirements.

Resource: Snowflake - What Is a Star Schema? A Complete Guide to Data Modeling - https://www.snowflake.com/en/fundamentals/star-schema/
## Misconception in My Track

## Open Question
