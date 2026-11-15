## Zadanie 1
```python
raw_country = " pl "
country = raw_country.strip()
print(country)
clean_country = country.upper()
print(clean_country)
```
## Zadanie 2
```python
raw_status = ' Paid '
status = raw_status.strip()
print(status)
clean_status = status.lower()
print(clean_status)
```
## Zadanie 3
```python
raw_amount = "129,99"
amount = raw_amount.replace(',','.')
clean_amount = float(amount)
print(clean_amount, type(clean_amount))
```
## Zadanie 4
```python
email = "ANNA.KOWALSKA@EXAMPLE.COM"
clean_email = email.lower()
print(clean_email)
if "@" in email:
    print('email contains @')
```
## Zadanie 5
```python
file_name = "orders_2026_10_12.json"
print(file_name.startswith('orders'))
print(file_name.endswith('json'))
```
## Zadanie 6
```python
line = "1001,paid,129.99"
order_id,status,amount = line.split(',')
print(order_id, status,amount)
```
## Zadanie 7
```python
customer_name = "Anna Kowalska"
orders_count = 3
total_revenue = 249.9
announcement = f'Klient {customer_name} ma {orders_count} o wartosci {total_revenue}'
print(announcement)
```
## Zadanie 8
```python
date = "2026-10-12"
page = 4
source = "orders"
file_path = f'data/raw/{source}_{date}_page_{page}.json'
print(file_path)
```
## Zadanie 9
```python
raw_country = None
country = ''
if raw_country == None:
    country = 'UNKNOWN'
else:
    country = raw_country.strip().upper()
print(country)
```
