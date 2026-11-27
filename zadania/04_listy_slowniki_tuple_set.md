## Zadanie 1
```python
customer = {
    'customer_id' : 1,
    'customer_name' : 'Anna Kowalska',
    'country' : 'PL',
    'email' : 'anna@example.com',
    'acquisition_channel' : 'newsletter'
}
print(customer)
print(customer['customer_name'])
print(customer['country'])
```
## Zadanie 2
```python
customer = {
    "customer_id": 1,
    "customer_name": "Anna Kowalska",
    "country": "PL",
}
email = customer.get('email','missing@example.com')
print(email)
```
## Zadanie 3
```python
order = {
    "order_id": 1001,
    "status": "new",
    "amount": 129.99,
}
order['status'] = 'paid'
order['country'] = 'PL'
print(order)
```
## Zadanie 4
```python
orders = [
{"order_id": 1001, "customer_id": 1, "status": "paid", "amount": 120.0},
{"order_id": 1002, "customer_id": 1, "status": "cancelled", "amount": 80.0},
{"order_id": 1003, "customer_id": 2, "status": "paid", "amount": 200.0}
    ]
print(orders)
```
## Zadanie 5
```python
orders = [
{"order_id": 1001, "customer_id": 1, "status": "paid", "amount": 120.0},
{"order_id": 1002, "customer_id": 1, "status": "cancelled", "amount": 80.0},
{"order_id": 1003, "customer_id": 2, "status": "paid", "amount": 200.0}
    ]
print(orders[0])
print(orders[1]['status'])
print(orders[2]['amount'])
print(orders[0]['customer_id'])
```
## Zadanie 6
```python
orders = [
{"order_id": 1001, "customer_id": 1, "status": "paid", "amount": 120.0},
{"order_id": 1002, "customer_id": 1, "status": "cancelled", "amount": 80.0},
{"order_id": 1003, "customer_id": 2, "status": "paid", "amount": 200.0}
    ]
orders.append({"order_id": 1004, "customer_id": 3, "status": "pending", "amount": 50.0})
print(orders)
print(len(orders))
```
## Zadanie 7
```python
countries = ["PL", "DE", "PL", "FR", "DE", "PL"]
unique_countries = set(countries)
print(unique_countries, type(unique_countries))
```
## Zadanie 8
```python
date_range = ('2026-10-01','2026-10-31')
print(date_range)
print(date_range[0])
print(date_range[1])
```
## Zadanie 9
```python
orders = [
    {"order_id": 1001, "customer": {"customer_id": 1, "name": "Anna"}, "amount": 120.0},
    {"order_id": 1002, "customer": {"customer_id": 2, "name": "Jan"}, "amount": 80.0},
]
print(orders[0]['customer']['name'])
print(orders[1]['customer']['customer_id'])
print(orders[1]['amount'])
```
## Zadanie 10
```python
countries = ["PL", "DE"]
countries.extend(['FR','IT'])
print(countries)
print(len(countries))
```
## Zadanie 11
```python
order = {
    "order_id": 1001,
    "status": "new",
    "total": 129.99,
}
order['status'] = 'paid'
order['country'] = 'PL'
print(order)
print(order.keys())
print(order.values())
print(order.items())
```
## Zadanie 12
```python
orders = [
    {"order_id": 1, "total": 100, "status": "paid"},
    {"order_id": 2, "total": 200, "status": "cancelled"},
]
first_order = orders[0]
print(first_order['status'])
print(orders[0]['status'])
```
## Zadanie 13
```python
orders = [{"id": 1}]
batch = [{"id": 2}, {"id": 3}]
orders.extend(batch)
print(orders)
print(len(orders))
print(orders[-1])
```
```python
orders = [{"id": 1}]
batch = [{"id": 2}, {"id": 3}]
orders.append(batch)
print(orders)
print(len(orders))
print(orders[-1])
```
## Zadanie 14
```python
queue = [1001, 1002, 1003, 1002]
current_id = queue.pop(0)
queue.remove(1002)
del queue[-1]
print(current_id)
print(queue)
queue.clear()
print(queue)
```
## Zadanie 15
```python
order_ids = [10, 20, 30, 40, 50, 60]
first_ids = order_ids[:3]
second_ids = order_ids[-2::]
third_ids = order_ids[::2]
fourth_ids = order_ids[::-1]
print(order_ids)
print(first_ids)
print(second_ids)
print(third_ids)
print(fourth_ids)
```
## Zadanie 16
```python
amounts = [200, 50, 100, 50]
amounts_sorted = (sorted(amounts, reverse=True))
print(amounts_sorted)
sort_result = amounts.sort()
print(amounts)
print(sort_result, type(sort_result))
```
## Zadanie 17
```python
order = {"id": 1, "status": "new", "debug": True}
changes = {"status": "paid", "country": "PL"}
was_debug = order.pop('debug')
order.update(changes)
order.pop('temporary_note', None)
print(was_debug, order)
```
