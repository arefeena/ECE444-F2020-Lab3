# ECE444-F2020-Lab3: Amar Arefeen

This repo is a clone of https://github.com/miguelgrinberg/flasky

## Activity 1

The screenshot below shows a successful run of the Chapter 3 examples from the textbook. It's been modified to show my name on the index page instead of `World` and uses `LLLL` verbosity for the timestamp instead of `LLL`, as directed by the assignment instructions.

![Successful run of Chapter 3 examples](/images/activity-1-success.png)

## Activity 2

The series of screenshots below show the email form validation in action. It also uses Jinja control structures to display different messages based on which domain the provided email address belongs to.

Welcome screen for a new user:

![Welcome screen for a new user](/images/activity-2-success-1.png)

Successful registration of user 'Amar' with a UofT email:

![Successful registration of user 'Amar' with a UofT email](/images/activity-2-success-2.png)

Error message generated by email validator:

![Error message generated by email validator](/images/activity-2-success-3.png)

Successful contact information change for 'Amar', now using a non-UofT email address:

![Successful contact information change for 'Amar', now using a non-UofT email address](/images/activity-2-success-4.png)

## Activity 3

SQL and NoSQL databases are two different approaches for storing data. Both are very powerful and for small- to medium-sized applications are practically equivalent in terms of performance.

The table below outlines some of the differences between the two:

| Topic | SQL | NoSQL |
| --- | --- | --- |
| Type  | **Relational** | Non-relational, **document-oriented** or **key-value** models |
| Data | Structured **records** stored in **tables** | Unstructured **documents** stored in **collections** |
| Flexibility | Fixed number of columns bound by a rigid **schema**, variable number of rows | Highly flexible, documents are not bound to a rigid schema (e.g. like JSON) and a collection can have a variable number of documents | 
| Relationships | Efficiently support **join** operations between tables through primary and foreign keys, which also decreases data duplication | Often do not support join operations; instead users must either store data **denormalised** (duplicated between collections) or have the client application perform the joining manually |
| Examples | Oracle Database, MySQL, Microsoft SQL Server, PostgreSQL | MongoDB, Redis, Elasticsearch, Apache Cassandra |
