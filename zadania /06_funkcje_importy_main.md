## Zadanie 1
```python
def normalize_country(country: str) -> str:
    return country.strip().upper()

print(normalize_country(" pl "))
print(normalize_country(" de "))
print(normalize_country(' Fr '))
```
## Zadanie 2
```python
def calculate_line_value(quantity: int, unit_price: float) -> float:
    return quantity * unit_price

print(calculate_line_value(3, 19.99))
```
## Zadanie 3
```python
def is_paid(status: str) -> bool:
     return status.strip().lower() == 'paid'
print(is_paid('paid'))
print(is_paid(' Paid '))
print(is_paid('cancelled'))
```
## Zadanie 4
```python
def get_order_value(order: dict) -> float:
    return order['quantity'] * order['unit_price']

print(get_order_value(order = {
    "order_id": 1001,
    "quantity": 4,
    "unit_price": 25.50,
}))
```
## Zadanie 5
```python
def build_order_summary(order: dict) -> dict:
    order_summary = order.copy()
    
order = {
    "order_id": 1001,
    "customer_id": 10,
    "quantity": 4,
    "unit_price": 25.50,
    "status": " Paid ",
}
```
