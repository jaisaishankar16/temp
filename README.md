Subject Areas = Typically relate to the top tier of a company’s logical structure, such as Human Resources, Finance, Sales, Manufacturing, and so on. A Subject Area provides a method for categorizing rules, datasets, and business processes. This module allows for easier management of Data Catalog features broken down by Subject Area.Every Rule and Business Process in the Data Catalog must belong to a Subject Area.
Business Processes = Business Processes are often set up by the workstream or business area, such as Order to Cash, Procure to Pay, Customer Master Data, or Material Master Data. A Business Process, like Order to Cash-Invoicing or Order to Cash-Shipping, represents an area of the business where you want to measure quality.You can calculate quality metrics based on all the Rules that are assigned to a particular process.
Dataset = A Dataset is associated with a System Datastore. It identifies which fields within the Datastore that make up that particular dataset. Datasets can be a subset of a single System or span Systems and tie the generic business-focused documentation of terms, policies and rules to where the data is stored.For example, a System Datastore might have 500 fields, but only 100 of those fields are associated with a particular Dataset.
Rules = Define data requirements from a business perspective. Rules are the foundation that data quality is built on. The Quality Process begins with Rules.
•	These define business data requirements and become the foundation that data quality is built on.
•	Rules can be assigned to one or more Business Processes or Business Concepts (Terms).
Business Concepts (Terms) = A Term, like Customer or Sales Order, represents a Business Concept. You can relate terms to Business Processes and Datasets, creating a comprehensive view of how assets interrelate to each other
Enforcements = Define validation requirements for a Rule, the system the Rule applies to, and the purpose of the Enforcement, such as Quality or Migration. Data Quality Enforcement defines the validation requirements for the Rule you looked at above. It identifies how you want to implement the Rule for Data Quality against a particular system. An Enforcement further defines a Rule. This identifies:
•	Specifications about the quality requirement and how it will be enforced.
•	Which System the rule applies to.
•	The purpose of the enforcement (such as Quality vs. Migration).
Implementations = Include the technical code used to execute the data analysis and validate whether it meets the Rule requirements. Implementation executes the analysis to validate whether data meets the Rule that you looked at above. Implementations are typically created by Developers. Using the documentation defined in the Enforcement, a technical team member, like Developer, writes technical code to execute (implement) the data analysis.
Opportunity Query = Defines the number of records in scope that the rule can apply to. This count is used to calculate your quality score.
Error Query = Defines exactly how the data is queried to determine which records are in error. The Error Query should always be a subset of the Opportunity Query.


