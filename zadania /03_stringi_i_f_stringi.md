## Zadanie 1
```python
raw_country = " pl "
country = raw_country.strip().upper()
print(country)
```
## Zadanie 2
```python
raw_status = " Paid "
status = raw_status.strip().lower()
print(status)
```
## Zadanie 3
```python
raw_amount = "129,99"
amount = float(raw_amount.replace(',','.'))
print(amount, type(amount))
```
## Zadanie 4
```python
email = "ANNA.KOWALSKA@EXAMPLE.COM"
lower_email = email.lower()
print(lower_email)

if '@' in email:
    print('email contains @')
```
## Zadanie 5
```python
file_name = "orders_2026_10_12.json"
beggining = file_name.startswith('orders')
ending = file_name.endswith('json')
print(beggining, ending)
```
## Zadanie 6
```python
line = "1001,paid,129.99"
columns = line.split(",")
print(columns)
print(f'order_id:{columns[0]},status:{columns[1]},amount:{columns[2]}')
```
## Zadanie 7
```python
customer_name = "Anna Kowalska"
orders_count = 3
total_revenue = 249.9
print(f'Klient {customer_name} ma {orders_count} zamówienia o wartości {total_revenue:.2f}')
```
## Zadanie 8
```python
date = "2026-10-12"
page = 4
source = "orders"
print(f'data/raw/{source}_{date}_page_{page}.json')
```
## Zadanie 9
```python

```
