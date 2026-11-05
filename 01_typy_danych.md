## Zadanie 1
```python
customer_name = "Anna Kowalska"
orders_count = 3
total_amount = 249.90
is_active = True
email = None
print(customer_name, type(customer_name))
print(orders_count, type(orders_count))
print(total_amount, type(total_amount))
print(is_active, type(is_active))
print(email, type(email))
```
## Zadanie 2
```python
raw_order_id = '1001'
raw_amount = '129.99'
raw_quantity = '3'
order_id = int(raw_order_id)
amount = float(raw_amount)
quantity = int(raw_quantity)
total_revenue = amount * quantity
print(total_revenue)
```
## Zadanie 3
```python
 order = {
    "order_id" : 1001,
    "customer_id" : 10,
    "country" : " pl ",
    "amount" : "129.99",
    "status" : "paid",
}
print(order['order_id'])
print(order['status'])
print(order['country'])
print(type(order['country']))
print(order['amount'])
amount = float(order['amount'])
```
## Zadanie 4
```python
order = {
    "order_id": 1001,
    "customer_id": 10,
    "amount": 129.99,
    "status": "paid",
}
discount = order.get('discount', 0)
print(discount)
```
## Zadanie 5
```python
orders = [
{"order_id": 1, "amount": 100.0, "status": "paid"},
{"order_id": 2, "amount": 200.0, "status": "cancelled"},
{"order_id": 3, "amount": 300.0, "status": "paid"}
]
print(orders[0])
print(orders[0]['status'])
print(orders[1]['amount'])
print(orders[2]['order_id'])
```
## Zadanie 6
```python
countries = ["PL","DE","PL","FR","DE","PL"]
countries = set(countries)
print(countries, type(countries))
```
## Zadanie 7
```python
date_range = ("2026-10-01","2026-10-31")
print(date_range)
print(date_range[0])
print(date_range[1])
print(type(date_range))
```
## Zadanie 8
```python
orders = [
    {"order_id": 1, "country": "PL", "amount": "100.50", "status": "paid"},
    {"order_id": 2, "country": "DE", "amount": "200.00", "status": "cancelled"},
    {"order_id": 3, "country": "FR", "amount": "300.25", "status": "paid"},
]
print(float(orders[0]['amount']))
print(orders[1]['country'])
print(orders[2]['status'])
summary = {
    'first_amount' : float(orders[0]['amount']),
    'second_country' : str(orders[1]['country']),
    'third_status' : str(orders[2]['status'])
}
print(summary)
```
## Zadanie 9
```python
raw_order_id = "1001"
raw_quantity = "3"
raw_unit_price = "19.99"
order_id = int(raw_order_id)
quantity = int(raw_quantity)
unit_price = float(raw_unit_price)
line_value = quantity * unit_price
print(order_id, type(order_id))
print(quantity, type(quantity))
print(unit_price, type(unit_price))
print(line_value, type(line_value))
```
## Zadanie 10
```python
print(0.1 + 0.2)
print(0.1 + 0.2 == 0.3)
from decimal import Decimal
amount = Decimal("0.1") + Decimal("0.2")
print(amount)
print(amount == Decimal("0.3"))
```
## Zadanie 11
```python
email_1 = None
email_2 = ""
orders_count = 0
print(email_1, type(email_1))
print(email_2, type(email_2))
print(orders_count, type(orders_count))
snapshot = {
    'email_1' : email_1,
    'email_2' : email_2,
    'orders_count' : orders_count
}
print(snapshot)
```
## Zadanie 12
```python
my_list = []
my_dict = {}
empty_set = set()
empty_tuple = ()
my_tuple = ("PL",)
print(my_list, type(my_list))
print(my_dict, type(my_dict))
print(empty_set, type(empty_set))
print(empty_tuple, type(empty_tuple))
print(my_tuple, type(my_tuple))
```
