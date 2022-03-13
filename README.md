# 3_OOP_Exercise_catalogue
Create a class Catalogue. The __init__ method should accept the name of the catalogue (string). Each catalogue should also have an attribute called products, an empty list. The class should also have three more methods:
•	add_product(product_name: str) - adds the product to the products' list
•	get_by_letter(first_letter: str) - returns a list containing only the products that start with the given letter
•	__repr__ - returns the catalogue info in the following format: 
"Items in the {name} catalogue:
{item1}
{item2}
…
{itemN}"
The items should be sorted alphabetically in ascending order.

Test Code
catalogue = Catalogue("Furniture")
catalogue.add_product("Sofa")
catalogue.add_product("Mirror")
catalogue.add_product("Desk")
catalogue.add_product("Chair")
catalogue.add_product("Carpet")
print(catalogue.get_by_letter("C"))
print(catalogue)

Output
["Chair", "Carpet"]
Items in the Furniture catalogue:
Carpet
Chair
Desk
Mirror
Sofa
