## Zadanie 1
```python
orders = [
    {"order_id": 1, "amount": 100.0, "status": "paid", "country": "PL"},
    {"order_id": 2, "amount": 200.0, "status": "cancelled", "country": "DE"},
    {"order_id": 3, "amount": 300.0, "status": "paid", "country": "PL"},
    {"order_id": 4, "amount": 50.0, "status": "pending", "country": "FR"},
    {"order_id": 5, "amount": 500.0, "status": "paid", "country": "DE"},
]
for order in orders:
    print(order['order_id')
```
## Zadanie 2
```python
orders_count = 0
orders = [
    {"order_id": 1, "amount": 100.0, "status": "paid", "country": "PL"},
    {"order_id": 2, "amount": 200.0, "status": "cancelled", "country": "DE"},
    {"order_id": 3, "amount": 300.0, "status": "paid", "country": "PL"},
    {"order_id": 4, "amount": 50.0, "status": "pending", "country": "FR"},
    {"order_id": 5, "amount": 500.0, "status": "paid", "country": "DE"},
]
for order in orders:
    orders_count += 1
print(orders_count)
```
## Zadanie 3
```python
paid_orders_count = 0
orders = [
    {"order_id": 1, "amount": 100.0, "status": "paid", "country": "PL"},
    {"order_id": 2, "amount": 200.0, "status": "cancelled", "country": "DE"},
    {"order_id": 3, "amount": 300.0, "status": "paid", "country": "PL"},
    {"order_id": 4, "amount": 50.0, "status": "pending", "country": "FR"},
    {"order_id": 5, "amount": 500.0, "status": "paid", "country": "DE"},
]
for order in orders:
    if order['status'] == 'paid':
        paid_orders_count = paid_orders_count + 1
print(paid_orders_count)
```
## Zadanie 4
```python
total_revenue = 0
orders = [
    {"order_id": 1, "amount": 100.0, "status": "paid", "country": "PL"},
    {"order_id": 2, "amount": 200.0, "status": "cancelled", "country": "DE"},
    {"order_id": 3, "amount": 300.0, "status": "paid", "country": "PL"},
    {"order_id": 4, "amount": 50.0, "status": "pending", "country": "FR"},
    {"order_id": 5, "amount": 500.0, "status": "paid", "country": "DE"},
]
for order in orders:
        total_revenue = order['amount'] + total_revenue
print(total_revenue)
```
## Zadanie 5
```python
paid_revenue = 0
orders = [
    {"order_id": 1, "amount": 100.0, "status": "paid", "country": "PL"},
    {"order_id": 2, "amount": 200.0, "status": "cancelled", "country": "DE"},
    {"order_id": 3, "amount": 300.0, "status": "paid", "country": "PL"},
    {"order_id": 4, "amount": 50.0, "status": "pending", "country": "FR"},
    {"order_id": 5, "amount": 500.0, "status": "paid", "country": "DE"},
]
for order in orders:
        if order['status'] == 'paid':
           paid_revenue += order['amount']
print(paid_revenue)
```
## Zadanie 6
```python
orders = [
    {"order_id": 1, "amount": 100.0, "status": "paid", "country": "PL"},
    {"order_id": 2, "amount": 200.0, "status": "cancelled", "country": "DE"},
    {"order_id": 3, "amount": 300.0, "status": "paid", "country": "PL"},
    {"order_id": 4, "amount": 50.0, "status": "pending", "country": "FR"},
    {"order_id": 5, "amount": 500.0, "status": "paid", "country": "DE"},
]
paid_orders = []
for order in orders:
    if order['status'] == 'paid':
        paid_orders.append(order)
print(paid_orders)
```
## Zadanie 7
```python

```
