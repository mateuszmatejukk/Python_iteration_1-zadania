## Zadanie 1
```python
customer_name = 'Anna Kowalska'
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
raw_order_id = "1001"
raw_amount = "129.99"
raw_quantity = "3"
order_id = int(raw_order_id)
amount = float(raw_amount)
quantity = int(raw_quantity)
total_amount = amount * quantity
print(total_amount)
```
## Zadanie 3
```python
order = {
    'order_id' : 1001,
    'customer_id' : 10,
    'country' : " pl ",
    'amount' : '129.99',
    'status' : 'paid'
 }
print(order['order_id'])
print(order['status'])
print(order['country'],type(order['country']))
print(order['amount'])
(order['amount']) = float(order['amount'])
print((order['amount']), type(order['amount']))
```
## Zadanie 4
```python
order = {
    "order_id": 1001,
    "customer_id": 10,
    "amount": 129.99,
    "status": "paid",
}
discount = order.get('discount',0)
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
```
```python
orders = [
{"order_id": 1, "amount": 100.0, "status": "paid"},
{"order_id": 2, "amount": 200.0, "status": "cancelled"},
{"order_id": 3, "amount": 300.0, "status": "paid"}
    ]
print(orders[0]['status'])
```
```python
orders = [
{"order_id": 1, "amount": 100.0, "status": "paid"},
{"order_id": 2, "amount": 200.0, "status": "cancelled"},
{"order_id": 3, "amount": 300.0, "status": "paid"}
    ]
print(orders[1]['amount'])
```
```python
orders = [
{"order_id": 1, "amount": 100.0, "status": "paid"},
{"order_id": 2, "amount": 200.0, "status": "cancelled"},
{"order_id": 3, "amount": 300.0, "status": "paid"}
    ]
print(orders[2]['order_id'])
```
## Zadanie 6
```python
countries = ["PL", "DE", "PL", "FR", "DE", "PL"]
proper_countries = set(countries)
print(proper_countries, type(proper_countries))
```
## Zadanie 7
```python
date_range = ('2026-10-01', '2026-10-31')
print(date_range, type(date_range))
print(date_range[0])
print(date_range[1])
```
## Zadanie 8
```python
orders = [
    {"order_id": 1, "country": "PL", "amount": "100.50", "status": "paid"},
    {"order_id": 2, "country": "DE", "amount": "200.00", "status": "cancelled"},
    {"order_id": 3, "country": "FR", "amount": "300.25", "status": "paid"},
]
(orders[0]['amount']) = float(orders[0]['amount'])
print((orders[0]['amount']), type((orders[0]['amount'])))
print(orders[1]['country'])
print(orders[2]['status'])
summary = {
    'first_amount' : float(orders[0]['amount']),
    'second_country' : orders[1]['country'],
    'third_status' : orders[2]['status']
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
```
```python
from decimal import Decimal
amount = Decimal('0.1') + Decimal('0.2')
print(amount)
print(amount == Decimal('0.3'))
```
## Zadanie 11
```python
email_1 = None
email_2 = ""
orders_count = 0
print(email_1, type(email_1))
print(email_2, type(email_2))
snapshot = {
    'email_1' : email_1,
    'email_2' : email_2,
    'orders_count' : orders_count
}
print(snapshot)
```
## Zadanie 12
```python
empty_list = []
empty_dictionary = {}
empty_set = set()
empty_tuple = ()
polish_tuple = ('PL',)
print(empty_list, type(empty_list))
print(empty_dictionary, type(empty_dictionary))
print(empty_set, type(empty_set))
print(empty_tuple, type(empty_tuple))
print(polish_tuple, type(polish_tuple))
```
## Zadanie 13
```python
from decimal import Decimal
raw_postal_code = "00123"
raw_quantity = "3"
raw_unit_price = "19.99"
line = {
    'postal_code' : raw_postal_code,
    'quantity' : int(raw_quantity),
    'unit_price' : Decimal(raw_unit_price)}
line['line_value'] = line['quantity'] * line['unit_price']

print(line)
```
## Zadanie 14
```python
from decimal import Decimal
response = {
    "source": "shop",
    "orders": [
        {"id": 101, "amount": "0.00", "tags": {"new", "web"}},
        {"id": 102, "amount": "25.50", "tags": set()},
    ],
    "date_range": ("2026-10-01", "2026-10-31"),
    "next_page": None,
}
print(response["orders"][1]['id']) ## pobrane ID drugiego zamówienia
print(response['orders'][0]['tags']) ## set tagi pierwszego zamówienia
print(response['date_range'][1]) ## końcowa data z tuple date_range
print(response['next_page']) ## pobrane next_page
new_response = {
    'order_id' : (response["orders"][1]['id']),
    'amount'  : Decimal(response['orders'][0]['amount']),
    'tags' : (response['orders'][0]['tags']),
    'date_range' : (response['date_range'][1]),
    'next_page' : (response['next_page'])
}
print(new_response)
```
