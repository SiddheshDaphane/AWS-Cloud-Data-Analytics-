# AWS-Cloud-Data-Analytics

## INTRODUCTION
The Chancellor's Office at Major University has embarked on a strategic initiative to
modernize its data and analytics capabilities. As enrollments spike in new online programs,
the limitations of current infrastructure are being exposed. Legacy systems, siloed data, and
rising costs threaten the University's ability to provide robust services that drive student
success.
A cross-functional team has been tasked with designing a unified, cloud-based platform to
consolidate the existing hybrid environment. This new architecture aims to enable
advanced analytics, improve data governance, reduce expenses, and scale to accommodate
rapid growth.

## PROBLEM BACKGROUND
Over the last decade, Major University has added a multitude of new systems as on-campus
and online courses expanded. With thousands of additional students and hundreds of
cohorts, managing the accompanying data has become an pressing challenge.
The current environment relies on dated solutions that create data silos and drive
complexity. A mix of on-premise and cloud databases power vendor and custom
applications, resulting in fractured views of information. As duplicative systems proliferate,
costs and data discrepancies balloon.
The outdated infrastructure hamstrings administrators’ ability to quickly deploy new
capabilities or generate insights through modern techniques like machine learning. Lacking
standardization and a "single source of truth" puts institutional analytics and reporting at
risk.

## OBJECTIVE
Our objective is to design and implement a robust, scalable data analytics platform on AWS
cloud that serves as the centralized data repository for the university. The key goal is to unify
disparate siloed data sources scattered across legacy on-prem systems, SaaS applications and
existing cloud deployments into an integrated data lake powered by capabilities for seamless
batch and real-time data ingestion.
Sophisticated data processing will structure unstructured content while master data
management will maintain data accuracy and single source of truth for key entities like
students, employees and courses. Easy self-service access coupled with customizable
dashboards, strong governance standards encompassing security, privacy and access controls
will enable democratized analytical insights for both technical and business users.
The platform aims to unlock advanced analytics through machine learning to answer critical
questions around student outcomes, optimal curriculum design, compliance monitoring etc.
Continual enhancement of predictive models and AI capabilities will establish thought
leadership for the university. Through reliable, scalable, cost-optimized design leveraging AWS
cloud, we target driving automation into data-intensive processes to inform strategic decisions
that significantly improve educational experiences and business efficiency.

## PROPOSED SOLUTION
The proposed cloud-native solution leverages AWS Lake Formation to establish a scalable
data lake ingesting batch and real-time streams. AWS Glue data catalog classifies datasets
while Spark processes transformations for analytical readiness. Granular access controls,
encryption enforced through Lake Formation coupled with CloudTrail, Macie enable trusted
governance. Kinesis Firehose, AppFlow and EventBridge drive continuous data integration.
Redshift Spectrum and SageMaker power ad-hoc querying over vast data scale and runway
for advanced machine learning in a serverless fashion - collectively realizing a high-
performance, cost-efficient analytics environment.

<img width="1130" alt="Screenshot 2024-05-31 at 7 56 15 AM" src="https://github.com/SiddheshDaphane/AWS-Cloud-Data-Analytics-/assets/105710898/85ce4d76-b1e2-4a99-b435-aacfa1fe1294">


### BATCH PROCESSING PIPELINE

<img width="784" alt="Screenshot 2024-05-31 at 8 03 52 AM" src="https://github.com/SiddheshDaphane/AWS-Cloud-Data-Analytics-/assets/105710898/890c6f3d-1172-490a-b1a7-f68342877fd2">

### REALTIME STREAMING PROCESSING PIPELINE

<img width="809" alt="Screenshot 2024-05-31 at 8 05 01 AM" src="https://github.com/SiddheshDaphane/AWS-Cloud-Data-Analytics-/assets/105710898/b44b1082-614c-48ad-afe8-f388c649b720">
