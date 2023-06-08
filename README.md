Create a MySQL database named "online_store".
Create a table named "categories" in the database. The table should have the following columns:

id: The primary key of the table.
name: The name of the category.
lft: The left-hand side of the category in the nested set tree.
rgt: The right-hand side of the category in the nested set tree.
created_at: The date and time the category was created.
updated_at: The date and time the category was updated.

<br>
Implement the nested set model for the "categories" table using Laravel's Eloquent ORM.
Design the API routes for category management. The following are the endpoints that you need to create:<br><br>
GET /categories: Retrieve all categories in XML format.<br>
GET /categories/{id}: Retrieve a specific category by its ID in XML format.<br>
POST /categories: Create a new category. Accept XML request payload with name and parent_id fields. Return the created category in XML format.<br>
PUT /categories/{id}: Update an existing category by its ID. Accept XML request payload with name field. Return the updated category in XML format.<br>
DELETE /categories/{id}: Delete a category by its ID. Return a success message in XML format.<br>


Implement the logic for each API endpoint using Laravel's routing, controllers, and models.
Ensure appropriate error handling and validation for the API endpoints. Return proper error responses in XML format for invalid requests.
Create sample categories in the database for testing purposes.
Write unit tests to cover the API endpoints and ensure their functionality.