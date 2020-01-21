1. Setup a virtual environment.
2. Fork the repository for [Django Task 10](https://github.com/JoinCODED/task_10), in JoinCODED’s Github and Clone it.
3. Install the packages from the requirements file.
4. Create a field called `owner` for the `Restaurant` model.
    * `ForeignKey` to the `User` model.
    * set a default value or delete the database.
5. Create a model called `Item` with the following fields:
    * `name`
    * `description`
    * `price`
    * `restaurant`: `ForeignKey` to the `Restaurant` model.
6. Adjust the `restaurant_create` view so that when a user who is logged in creates a `Restaurant` object, they get assigned as the `owner`.
7. The `item_create` view has been partially written for you, complete it:
    * The user should only input the `name`, `description`, and `price`.
    * The `restaurant` should be assigned automatically.
    * After creating an Item you should be redirected to the `restaurant_detail` page.
    * Display a **Create Item** button in the **restaurant detail** page.
8. The URL for `item_create` has been partially written for you, complete it.
9. Display a list of items belonging to the restaurant in the **restaurant detail** page.
10. Pass the tests.
11. Push your code.
.
