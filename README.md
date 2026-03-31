# Unknown App Reengineering

## 3. Use Case Diagram

```mermaid
actor Student
actor Admin

Student --> (Create Student Profile)
Student --> (Login / Access System)
Student --> (Register for Course)
Student --> (Drop Course)
Student --> (View Schedule)
Student --> (View Billing Summary)
Student --> (Edit Profile)

Admin --> (Add Course)
Admin --> (View All Courses)
Admin --> (View All Students)
Admin --> (View Course Roster)
Admin --> (Manage Student Records)

(Register for Course) --> (Check Availability)
(Register for Course) --> (Check Time Conflict)
(Drop Course) --> (Update Enrollment)

### Flowchart of the main workflow

### Prompts
