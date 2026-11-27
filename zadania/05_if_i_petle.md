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

## Zadanie 3
```python
orders = [
    {"order_id": 1, "amount": 100.0, "status": "paid", "country": "PL"},
    {"order_id": 2, "amount": 200.0, "status": "cancelled", "country": "DE"},
    {"order_id": 3, "amount": 300.0, "status": "paid", "country": "PL"},
    {"order_id": 4, "amount": 50.0, "status": "pending", "country": "FR"},
    {"order_id": 5, "amount": 500.0, "status": "paid", "country": "DE"},
]
paid_orders_count = 0
for order in orders:
    if order['status'] == 'paid':
        paid_orders_count += 1
print(paid_orders_count)
```
## Zadanie 4
```python
orders = [
    {"order_id": 1, "amount": 100.0, "status": "paid", "country": "PL"},
    {"order_id": 2, "amount": 200.0, "status": "cancelled", "country": "DE"},
    {"order_id": 3, "amount": 300.0, "status": "paid", "country": "PL"},
    {"order_id": 4, "amount": 50.0, "status": "pending", "country": "FR"},
    {"order_id": 5, "amount": 500.0, "status": "paid", "country": "DE"},
]
total_revenue = 0
for order in orders:
    total_revenue += order['amount']
print(total_revenue)
```
## Zadanie 5
```python
paid_revenue = 0
for order in orders:
    if order['status'] == 'paid':
        paid_revenue += order['amount']
print(paid_revenue)
```
## Zadanie 6
```python
paid_orders = []
for order in orders:
    if order['status'] == 'paid':
        paid_orders.append(order)
print(paid_orders)
```
## Zadanie 7
```python
high_value_orders = []
for order in orders:
    if order['amount'] >= 200:
        high_value_orders.append(order)
print(high_value_orders)
```
## Zadanie 8
```python
pl_orders_count = 0
for order in orders:
    if order['country'] == 'PL':
        pl_orders_count += 1
print(pl_orders_count)
```
## Zadanie 9
```python
for order in orders:
    print(f'Order {order["order_id"]} is {order["status"]}')
```
## Zadanie 10
```python
for order in orders:
    if order['status'] == 'cancelled':
        continue
    print(order)
```
## Zadanie 11
```python
for order in orders:
    if order['amount'] >= 300:
        print(order)
        break
```
## Zadanie 12
```python
orders_count = 0
paid_orders_count = 0
cancelled_orders_count = 0
pending_orders_count = 0
total_revenue = 0
paid_revenue = 0
high_value_orders_count = 0
for order in orders:
    orders_count += 1

for order in orders:
    if order['status'] == 'paid':
        paid_orders_count += 1

for order in orders:
    if order['status'] == 'cancelled':
        cancelled_orders_count += 1

for order in orders:
    if order['status'] == 'pending':
        pending_orders_count += 1

for order in orders:
    total_revenue += order['amount']

for order in orders:
    if order['status'] == 'paid':
        paid_revenue += order['amount']

for order in orders:
    if order['amount'] >= 200:
        high_value_orders_count += 1
```
