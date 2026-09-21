| Test Case ID | Module               | Test Scenario                | Test Input                      | Expected Result                        |
| ------------ | -------------------- | ---------------------------- | ------------------------------- | -------------------------------------- |
| TC01         | Login                | Login with valid credentials | Valid username and password     | User should log in successfully        |
| TC02         | Login                | Login with invalid password  | Valid username + wrong password | Error message should be displayed      |
| TC03         | Student Registration | Register a new student       | Valid student details           | Student should be registered           |
| TC04         | Student Registration | Submit empty required fields | Empty fields                    | Validation message should be displayed |
| TC05         | Room Allocation      | Allocate an available room   | Valid student + available room  | Room should be allocated               |
| TC06         | Room Allocation      | Allocate an occupied room    | Occupied room                   | System should prevent allocation       |
| TC07         | Mess Management      | Add a mess ticket            | Valid food/mess request         | Mess ticket should be created          |
| TC08         | Complaint Management | Submit a complaint           | Valid complaint details         | Complaint should be recorded           |
| TC09         | Fee Management       | Record fee payment           | Valid payment details           | Payment should be recorded             |
| TC10         | Logout               | Logout from the system       | Click Logout                    | User should be logged out              |
