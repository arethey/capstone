MANAGE STUDENT
- student no.
- lastname
- firstname
- middlename
- course
- curriculum

MANAGE COURSE
- course code
- description

MANAGE CURRICULUM
- curriculum
- course id - foreign key
- descriptive

MANAGE SUBJECTS
- curriculum id - foreign key
- year level id - foreign key
- semester
- subject code
- descriptive
- total units
- pre-requisite

EVALUATION
- student id
- subject id
- academic year id
- grade

MANAGE ACADEMIC YEAR
- year
- semester
- status

STUDENT RECORDS
- get from evaluation
- filter by academic year and student

CREDIT COURSE
- subject id
- student id
- grade