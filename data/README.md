## Dataset Details

### Overview
The datasets used in this project encompass comprehensive records of supplier profiles, historical activities, and performance indicators. They are structured to support modeling phases related to supplier onboarding and allocation processes.

### Data Composition

**Supplier Entry Phase**  
Contains data reflecting supplier characteristics such as identity, financial capability, certifications, and historical supply information, alongside performance metrics utilized as prediction targets.

**Supplier Allocation Phase**  
Includes longitudinal data capturing supplier behavior and performance over consecutive time intervals, enabling dynamic assessment of their responsiveness, technical quality, bidding outcomes, quality compliance, and punctuality.

### Dataset Structure

**Input Features**  
Attributes representing supplier profiles, financial and technical capabilities, delivery history, and quality control data.

**Output Variables**  
Performance indicators aligned with supplier responsiveness, proposal quality, bid success, quality control adherence, and timeliness.

### Data Preprocessing and Integration

Extensive preprocessing steps have been undertaken, including:

- Data cleaning to remove missing or inconsistent entries.
- Outlier detection and correction.
- Normalization and scaling of features to enhance model stability.
- Integration of multiple raw data sources from internal systems, ensuring consistent and accurate linkage by supplier codes.
- Aggregation of data across time periods for time-series analysis in the allocation phase.

### Confidentiality Notice
Due to the sensitive nature of the company’s proprietary data, raw datasets cannot be shared publicly.
