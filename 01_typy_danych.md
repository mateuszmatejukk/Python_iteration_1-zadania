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

```
