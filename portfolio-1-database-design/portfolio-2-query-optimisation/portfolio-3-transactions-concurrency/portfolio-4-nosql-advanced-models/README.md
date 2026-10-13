# Activity 4: NoSQL and Advanced Data Models

## Aim
This activity demonstrates how a document-oriented NoSQL database can store hospital patient information.

## Database Used
MongoDB Atlas.

## Implementation
A database named `hospital_nosql` contains a `patients` collection. A sample patient document uses fields such as `patientCode`, `firstName`, `lastName`, and `gender`. An embedded `appointments` array stores appointment details alongside the patient record.

## Query Test
The filter `{ "patientCode": "PAT1001" }` was used to find the sample patient document.

## Advantages
- Flexible document structure.
- Related appointment details can be stored inside a patient document.
- Useful for records that contain nested or changing information.

## Considerations
Embedding appointments may create duplication or make updates harder when appointments need to be shared across different records. The relational PostgreSQL design remains useful for enforcing relationships and constraints.

## Evidence
Screenshots of the MongoDB collection and patient document will be added to the `screenshots` folder.

## Conclusion
MongoDB provides a flexible way to represent patient records and embedded appointment details. The best data model depends on the application's requirements.
