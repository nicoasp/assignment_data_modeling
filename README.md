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
	id - INT PK
	name - VARCHAR(64)

Links
	id - INT PK
	link - VARCHAR(64)
	user_id - INT FK

Comments
	id - INT PK
	user_id - INT FK
	body - VARCHAR(255)
	parent__id - INT FK
	parent_type - TEXT




Advanced
Users to Orders one to many
Orders to Products many to many
Shipments to Orders one to many


Users
	id - INT PK
	f_name - VARCHAR(64)
	l_name - VARCHAR(64)

Address
	id - INT PK 
	user_id - INT FK
	street_name - VARCHAR(64)
	street_number - TINYINT
	apartment_number
	city_id - INT FK
	state_id - INT FK
	country_id - INT FK
	zip_id - INT FK	

Products
	id - INT PK
	name - VARCHAR(64)
	price - DECIMAL
	stock - INTEGER

	OrderProducts
		id - INT PK
		quantity - INTEGER
		product_id - INT FK
		order_id - INT FK
		

Orders
	id - INT PK
	user_id - INT FK
	shipment_id - INT FK


Shipments
	id - INT PK




