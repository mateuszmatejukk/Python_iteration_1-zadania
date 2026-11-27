## Zadanie 1
```python
def normalize_country(country: str) -> str:
   return country.strip().upper()
print(normalize_country(" pl "))
print(normalize_country("de"))
print(normalize_country(" Fr "))
```
## Zadanie 2
```python
def calculate_line_value(quantity: int, unit_price: float) -> float:
    return quantity * unit_price
print(calculate_line_value(3,19.99))
```
## Zadanie 3
```python
def is_paid(status: str) -> bool:
    if status.strip().lower() == 'paid':
        return True
print(is_paid("paid"))
print(is_paid(" Paid "))
print(is_paid("cancelled"))
```
## Zadanie 4
```python
def get_order_value(order: dict) -> float:
    return order['unit_price'] * order['quantity']

order = {
        "order_id": 1001,
        "quantity": 4,
        "unit_price": 25.50,
    }
print(get_order_value(order))
```
## Zadanie 5
```python
def build_order_summary(order: dict) -> dict:
    return {
        'order_id': order['order_id'],
        'customer_id': order['customer_id'],
        'order_value': order['quantity'] * order['unit_price'],
        'is_paid' :  order['status'].strip().lower() == 'paid'
    }



order = {
        "order_id": 1001,
        "customer_id": 10,
        "quantity": 4,
        "unit_price": 25.50,
        "status": " Paid ",
    }
print(build_order_summary(order))
```
## Zadanie 6
```python
def get_order_segment(order_value: float) -> str:
    if order_value >= 200:
        return 'high'
    elif order_value >= 100:
        return 'medium'
    else:
        return 'low'
print(get_order_segment(200))
```
## Zadanie 7
```python
def get_order_segment(order_value: float) -> str:
    if order_value >= 200:
        return 'high'
    elif order_value >= 100:
        return 'medium'
    else:
        return 'low'

def transform_order(raw_order: dict) -> dict:
    amount = float(raw_order['amount'])
    return {
        'order_id': int(raw_order['id']),
        'country': raw_order['country'].strip().upper(),
        'amount': float(raw_order['amount']),
        'status': raw_order['status'].strip().lower(),
        'segment': get_order_segment(amount)
    }

raw_order = {
    "id": "1001",
    "country": " pl ",
    "amount": "250.50",
    "status": " Paid ",
}
print(transform_order(raw_order))
```
