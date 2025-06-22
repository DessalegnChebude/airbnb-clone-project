# airbnb-clone-project
#### airbnb-clone project for my prodev backend class practice
# Project overview
#### The backend for the Airbnb Clone project is designed to provide a robust and scalable foundation for managing user interactions, property listings, bookings, and payments. This backend will support various functionalities required to mimic the core features of Airbnb, ensuring a smooth experience for users and hosts.
## The Goal of the project is
1. User Management: Implement a secure system for user registration, authentication, and profile management.
2. Property Management: Develop features for property listing creation, updates, and retrieval.
3. Booking System: Create a booking mechanism for users to reserve properties and manage booking details.
4. Payment Processing: Integrate a payment system to handle transactions and record payment details.
5. Review System: Allow users to leave reviews and ratings for properties.
6. Data Optimization: Ensure efficient data retrieval and storage through database optimizations.
## Technology Stack
**Django:** A high-level Python web framework used for building the RESTful API.\
**Django REST Framework:** Provides tools for creating and managing RESTful APIs.\
**PostgreSQL:** A powerful relational database used for data storage.\
**GraphQL:** Allows for flexible and efficient querying of data.\
**Celery:** For handling asynchronous tasks such as sending notifications or processing payments.\
**Redis:** Used for caching and session management.\
**Docker:** Containerization tool for consistent development and deployment environments.\
**CI/CD Pipelines:** Automated pipelines for testing and deploying code changes.\
## Team Roles
#### The team role consists of The following
1. **Backend Developer:** Responsible for implementing API endpoints, database schemas, and business logic.\
2. **Database Administrator:** Manages database design, indexing, and optimizations.\
3. **DevOps Engineer:** Handles deployment, monitoring, and scaling of the backend services.\
4. **QA Engineer:** Ensures the backend functionalities are thoroughly tested and meet quality standards.\

## Technology Stack
1. **Django:** A high-level Python web framework used for building the RESTful API.\
2. **Django REST Framework:** Provides tools for creating and managing RESTful APIs.\
3. **PostgreSQL:** A powerful relational database used for data storage.\
4. **GraphQL:** Allows for flexible and efficient querying of data.\
5. **Celery:** For handling asynchronous tasks such as sending notifications or processing payments.\
6. **Redis:** Used for caching and session management.\
7. **Docker:** Containerization tool for consistent development and deployment environments.\
8. **CI/CD Pipelines:** Automated pipelines for testing and deploying code changes.\
## Database Design Overview
#### The database design schema will have the following entities with their respective attributes
**Users:** a user can have the following attributes\
-
    **id:** a user can have unique ID\
    **name:** user can have a name.\
    **email**: user can have email adress.\
    **telephone:** a user can have telephone number\

**properties:** a property can have the following attribut.\
-
    **id:** a Property can have unique ID\
    **name:** Property can have a name.\
    **price**: Property can have a price tag.\
    **measure:** a Property can have a measure in number\

**booking:** this booking entity will have the following atribute\
-
    **id:** a booking can have unique ID\
    **gust_name:** booking can have a gust name.\
    **checkin_time**: booking can have check_in time .\
    **check_out_time:** a booking can have checkout time\

**reviews**: the review entity will have the following attribute\
-
    **id:** a review can have unique ID\
    **user:** review can have a a user who gives the review.\
    **description**: review can have description .\
    **date:** a review can have date time\

**payment:** the payment entity will have the following attribute\
-
    **transaction_id:** a payment can have unique transaction_id\
    **amount:** payment can have amount to be paid.\
    **description**: payment can have payment description .\
    **date:** a payment can have date time\