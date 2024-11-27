***Admission Number ***
    ***168051***
# E-Commerce Django Project

This project implements a simple e-commerce system with a `Customer` and `Order` model. Each customer can place multiple orders, but each order belongs to only one customer.

### Setup Instructions

1. **Clone the repository**:
***on gitbash terminal**
   git clone https://github.com/mbotejoy/API_Cat2.git
   cd ecommerce_project

2. **Setup Virtual Environment**:
***on the gitbash terminal**
  python3 -m venv venv
  source venv\Scripts\activate

3. **Install independencies**:
   pip install -r requirements.txt

4. **Apply migrations**:
python manage.py migrate
**Thpugh i was having problems in this step I ensured the path to where the mange.py file was located was correct using 
'$ cd "C:\Users\nyath\OneDrive\Desktop\2.2 LAB WORKS\API_Cat2\ecommerce_project"'

5. **Run the Development server**:
python manage.py runserver


