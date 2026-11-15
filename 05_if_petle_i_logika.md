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
    print(order['order_id'])
```
## Zadanie 2
```python
orders = [
    {"order_id": 1, "amount": 100.0, "status": "paid", "country": "PL"},
    {"order_id": 2, "amount": 200.0, "status": "cancelled", "country": "DE"},
    {"order_id": 3, "amount": 300.0, "status": "paid", "country": "PL"},
    {"order_id": 4, "amount": 50.0, "status": "pending", "country": "FR"},
    {"order_id": 5, "amount": 500.0, "status": "paid", "country": "DE"},
]
orders_count = 0
for order in orders:
    orders_count += 1
print(orders_count)
```
