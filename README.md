# assignment_data_modeling
Mmmmm.... dataaaaa....

*Include your ERM modeling "pseudocode" in the space below*

BASIC 1:

Courses
	course_id - INTEGER PK
	title - VARCHAR
	description - TEXT

Lessons
	lesson_id - INTEGER PK
	title - VARCHAR
	body - TEXT
	course_id - INTEGER FK



BASIC 2:

User
	id - INTEGER PK
	username - VARCHAR(64)
	email - VARCHAR(64)

Profile
	id - INTEGER PK
	user_id - INTEGER FK
	city_id - INTEGER FK
	state_id - INTEGER FK
	country_id - INTEGER FK
	age - TINYINT
	gender - CHAR(1)

City
	id - INTEGER PK
	name - VARCHAR(64)

State
	id - INTEGER PK
	name - VARCHAR(64)

Country
	id - INTEGER PK
	name - VARCHAR(64)





INTERMEDIATE:

Users


Links


Comments






