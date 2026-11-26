## mini cwiczenie
```python
raw_country = " de "
raw_amount = "250.00"
status = "paid"
country = raw_country.strip().upper()
amount = float(raw_amount)
is_paid = status == 'paid'
check_amount = amount >= 200
check_country = country in ['PL','DE','FR']
include_in_report = is_paid and check_amount and check_country
print(include_in_report)
```
## Zadanie 1
```python
customer_name = 'Anna Kowalska'
orders_count = 3
paid_orders_count = 2
cancelled_orders_count = 1
total_revenue = 249.90
print(customer_name, type(customer_name))
print(orders_count, type(orders_count))
print(paid_orders_count, type(paid_orders_count))
print(cancelled_orders_count, type(cancelled_orders_count))
print(total_revenue, type(total_revenue))
```
## Zadanie 2
```python
quantity = 3
unit_price = 19.99
line_value = quantity * unit_price
line_value_with_tax = line_value * 1.23
print(line_value)
print(line_value_with_tax)
```
## Zadanie 3
```python
orders_count = 0
orders_count += 1
orders_count += 1
orders_count += 1
print(orders_count)
```
## Zadanie 4
```python
status = "paid"
total_amount = 350
country = "PL"
is_paid = status == 'paid'
is_high_value = total_amount >= 300
is_polish_customer = country == 'PL'
print(is_paid)
print(is_high_value)
print(is_polish_customer)
```
## Zadanie 5
```python
status = "paid"
total_amount = 350
country = "PL"
include_in_report = status == 'paid' and total_amount >= 300 and country == 'PL'
print(include_in_report)
```
## Zadanie 6
```python
country = 'DE'
core_countries = ['PL','DE','FR']
is_core_countries = country in core_countries
print(is_core_countries)
```
## Zadanie 7
```python
country = "DE"
raw_amount = "250.00"
status = "paid"
amount = float(raw_amount)
check_country = country in ['PL','DE','FR']
amount_checker = amount >= 200
status_checker = status == 'paid'
include_in_report = check_country and amount_checker and status_checker
print(include_in_report)
```
## Zadanie 8
```python
total_amount = 120
if total_amount > 300 :
    order_tier = 'high'
else:
    order_tier = 'standard'
print(order_tier)
```
## Zadanie 9
```python
first = 2 + 3 * 4
second = (2 + 3) * 4
difference = first - second
print(first,second, difference)
```
## Zadanie 10
```python
status = "paid"
total_amount = 350
country = "PL"
is_paid = status == 'paid'
is_high_value = total_amount >= 300
is_core_country = country in ['PL','DE','FR']
include_in_report = is_paid and is_high_value and is_core_country
print(include_in_report)
```
## Zadanie 11
```python
status = "paid"
country = "DE"
total_amount = 180
include_in_report = status == 'paid' and country in ['PL','DE'] and total_amount >= 100
print(include_in_report)
```
## Zadanie 12
```python
status = "pending"
country = "DE"
amount = 150
is_blocked = False
can_include = status == 'paid' and country in ['PL','DE'] and amount >= 100 and is_blocked == False
print(can_include)
```
```python
status = "paid"
country = "DE"
amount = 150
is_blocked = True
can_include = status == 'paid' and country in ['PL','DE'] and amount >= 100 and is_blocked == False
print(can_include)
```
## Zadanie 13
```python
stock = 12
sold_quantity = 3
returned_quantity = 1
stock_after_sale = stock - sold_quantity
stock_after_refund = stock_after_sale + returned_quantity
needs_restock = stock_after_refund < 10
print(stock_after_sale)
print(stock_after_refund)
print(needs_restock)
```
## Zadanie 14
```python
amount_1 = 299
amount_2 = 300
amount_3 = 301
is_high_1 = amount_1 >= 300
print(is_high_1)
is_high_2 = amount_2 >= 300
print(is_high_2)
is_high_3 = amount_3 >= 300
print(is_high_3)
dictionaries  = [
    {'amount' : amount_1, 'is_high' : is_high_1},
    {'amount' : amount_2,'is_high' : is_high_2},
    {'amount' : amount_3,'is_high' : is_high_3}
]
print(dictionaries)
amount = 300
if amount >= 300:
    label = 'high'
else:
    label = 'standard'
```
## Zadanie 15
```python

```
