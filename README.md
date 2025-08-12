# REDCap Project Design Guidelines

## Overview
This guidelines covers topics on how to design a REDCap project with best practices in mind.  A basic understanding of designing a REDCap project is required to understand this guidelines. You can use this set of guidelines, fork them or make your own - the key here is that you pick a style and stick to it. To suggest changes or fix bugs please open an issue or pull request on GitHub.  If you wish to contribute to this guidelines, please contact me.

## Purpose
The purpose of the guidelines is to promote the adoption of best practices in designing REDCap projects. By following these standards, users can ensure their projects are consistent, easy to understand, and straightforward to hand over to new team members. Standardized design practices simplify training, improve collaboration, and reduce the learning curve for both creators and end-users. These guidelines aim to foster a uniform approach that enhances project usability, supports data integrity, and ensures projects are scalable, reproducible, and well-documented for long-term success.

## General

## Naming Conventions
### Uniform suffixes
The following suffixes have a universal meaning ensuring the field can be understood easily. Use the correct suffix where appropriate.

- _id—a unique identifier such as a column that is a primary key of another system.
- _name—signifies a name such as first_name.
- _addr—an address for the record could be physical or intangible such as pat_addr.
- _calc—a calculated field
- _desc—a descriptive text, usually used to contain embedded fields
- _status—flag value or some other status of any type such as registry_status.
- _total—the total or sum of a collection of values.
- _num—denotes the field contains any kind of number.
- _dt—denotes a column that contains the date of something.

## Choosing Field Types

### Radio vs Dropdown

### Checkboxes
Instead of using 1, 2, 3, you can use a text, so when presented, it will have more meaningful description.
(example)

## Record ID
Unique ID should be written down and remembered when searching/adding.  When the project contains 20K records, it will help in searching the database.
