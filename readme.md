# Features

Fully functional eCommerce web application with user and guest checkout functionality.

The eCommerce web app will allow users to add multiple products to their carts, including physical and digital products.

Payment integration will be handled primarily through PayPal for international availability and security.

The we will support both authenticated user and guest checkout processes.

Authenticated users can view pending and previous orders, while guests will have the option to create an account after a successful purchase.

# Project Structure:
The core structure of the project is outlined. It includes three main templates: `store.html`, `cart.html`, and `checkout.html`.

Additionally, there are six models defined:
```
USER
CUSTOMER
PRODUCT
ORDER
ORDERITEM
SHIPPING
```

# Download & Setup Instructions
1 - Clone the project:
- `git clone https://github.com/NirajanMahara/python-django-ecommerce.git`

2 - Navigate to the project directory:
- `cd ecommerce` or search root folder containing `manage.py`

3 - Create a virtual environment:
- Run `python3 -m venv <name_of_virtualenv>`
- Example `python3 -m venv myenv`

4 - Activate the virtual environment:

- For Windows: `myenv\scripts\activate`
- For Unix/Mac: `source myenv/bin/activate`

5 - Install project dependencies:
- `pip install -r requirements.txt`

6 - Run the Django server: 
- `python manage.py runserver`