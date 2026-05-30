# Database Schema Reference

Detailed configurations of Mongo DB Mongoose structures.

## User Schema
- `username`: String (Required)
- `email`: String (Required, Unique)
- `password`: String (Required)
- `college`: String (Required)
- `year`: String (Required)
- `completedLessons`: Array of ObjectIds
