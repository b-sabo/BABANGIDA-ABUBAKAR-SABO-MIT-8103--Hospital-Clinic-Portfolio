# Activity 2: Query Processing and Optimisation

**Case Study:** Hospital/Clinic Management System

## Objective
To retrieve hospital records using SQL and examine query execution plans and indexing.

## Practical Work
- Used SQL JOIN queries to combine patient, doctor, and appointment records.
- Used `EXPLAIN ANALYZE` to examine query execution.
- Created an index on `appointments.appointment_time`.
- Examined how query plans may differ before and after indexing.

## Evidence
Add screenshots of the JOIN results, execution plans, and successful index creation here.

## Observation
An index can help with date-based searches and sorting, but PostgreSQL may choose a sequential scan when the dataset is small.
