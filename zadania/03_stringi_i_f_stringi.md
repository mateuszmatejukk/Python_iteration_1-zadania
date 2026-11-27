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
cleaned_mail = email.lower()
if '@' in cleaned_mail:
    print('email contains @')
print(cleaned_mail)
```
## Zadanie 5
```python
file_name = "orders_2026_10_12.json"
print(file_name.startswith('orders'))
print(file_name.endswith('.json'))
```
## Zadanie 6
```python
line = "1001,paid,129.99"
splited_line = line.split(',')
print(splited_line)
print(f'order_id:{splited_line[0]}\n status:{splited_line[1]}\namount:{splited_line[2]}')
```
## Zadanie 7
```python
customer_name = "Anna Kowalska"
orders_count = 3
total_revenue = 249.9
print(f'Klient {customer_name} ma {orders_count} zamowienia o wartosci {total_revenue:.2f}')
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
raw_country = None
if raw_country is None:
    country = 'UNKNOWN'
else:
    country = raw_country.strip().upper()
print(country)
```
## Zadanie 10
```python
country = " pl "
new_country = country.strip().upper()
print(new_country)
```
## Zadanie 11
```python

```
