## Database Conventions
* Append `_envname` to database name. Such as:
    * appinionfieldforce_dev
    * appinionfieldforce_local
    * appinionfieldforce_uat
* Collation should be: `utf8_unicode_ci/utf8mb4_unicode_ci`
* Table storage engine/type should be: `innoDB`
* Master table name should be snake_case & pluralized. Ex:
    * users, posts, transactions, product_categories
* Pivot table name should be snake_case. Ex:
    * Good Ex: order_product, post_comment, user_role
* A master table must have a primary key column named `id`.
    * Bad primary key column name: tbl_project_id, tbl_user_role_id
    * Do not use `big integer` for primary key if not actually required
    * Its a good practice to keep the primary key as `unsigned integer`
* Any relation column must be `foreign key` constrained
* Foreign key column name should be model name(singular) with `_id` appended to it:
    * Good ex: user_id, customer_id, category_id, project_id
    * Bad ex: tbl_user_user_id, tbl_project_info_tbl_project_info_id

**N.B:** Mostly try to follow naming conventions of laravel