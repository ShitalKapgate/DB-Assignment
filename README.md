Question no.1 Answer:-
The ralationship between the "product" and "product_category" entities is established through a foreign key in the "product" table.
Specifically, the "  category_id"column in the "product" table serves as a foreign key that references the primary key "id" in the "Product_catogory" table. this indicates that each product is associated with a specific category, and the "category_id" in the "product" table points to the corresponding category in the "product_category" table.   This relationship allows for categorizing product and organizing them based on characteristics or Attributes.

Question no.2 Amswer:-
   To ensure that each product in the "product" table has a valid category assigned to it, you can define a foreignkey constraint on the "category_id" column in the "product" table.
