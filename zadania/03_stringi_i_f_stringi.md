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
email_1 = None
email_2 = ""
email_3 = "   "
email_4 = " ANNA@EXAMPLE.COM "
if email_1 is None:
    print('missing')
elif email_1.strip() == '':
    print('empty')
else:
    print(email_1.strip().lower())
if email_2 is None:
    print('missing')
elif email_2.strip() == '':
    print('empty')
else:
    print(email_2.strip().lower())
if email_3 is None:
    print('missing')
elif email_3.strip() == '':
    print('empty')
else:
    print(email_3.strip().lower())
if email_4 is None:
    print('missing')
elif email_4.strip() == '':
    print('empty')
else:
    print(email_4.strip().lower())
```
## Zadanie 12
```python
file_name = " orders_2026_10_10.JSON "
cleaned_file_name = file_name.strip().lower()
beginning = cleaned_file_name.startswith('orders')
ending = cleaned_file_name.endswith('.json')
print(cleaned_file_name)
print(beginning)
print(ending)
```
## Zadanie 13
```python
file_name = "orders_2026-10-12_PL.csv"
file_source = file_name[0:6]
file_date = file_name[7:17]
file_country = file_name[18:20]
file_extension = file_name[21:24]
file_info = {
    'source' : file_source,
    'date' : file_date,
    'country' : file_country,
    'extension' : file_extension
}
print(file_info)
print(file_name[-3::])
print(file_name[::2])
print(file_name[::-1])
```
## Zadanie 14
```python
raw_line = " 1001   paid   PL "
raw_row = "1001||PL|"
print(raw_line.split())
print(raw_row.split('|'))
```
## Zadanie 15
```python
columns = ["order_id", "status", "amount"]
header = f'{columns[0]};{columns[1]};{columns[2]}.'
print(header)
```
## Zadanie 16
```python
from decimal import Decimal

amount = Decimal("129.995")
print(f'Amount: {amount:.2f} PLN')
print(amount, type(amount))
```
## Zadanie 17
```python
from decimal import Decimal
raw_id = " 1001 "
raw_status = " PAID "
raw_amount = " 120,50 "
order = {
    'id' : int(raw_id),
    'status' : raw_status.strip().lower(),
    'amount' : Decimal(raw_amount.strip().replace(',','.'))
}
print(f'Order {order['id']}: {order['status']}, amount = {order['amount']}')
print(raw_amount)
```
