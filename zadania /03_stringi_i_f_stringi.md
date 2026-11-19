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
    clean_mail_1 = 'missing'
elif email_1.strip() == "":
    clean_mail_1 = 'empty'
else:
    clean_mail_1 = email_1.strip().lower()
print(clean_mail_1)
if email_2 is None:
    clean_email_2 = 'missing'
elif email_2.strip() == "":
    clean_mail_2 = 'empty'
else:
    clean_mail_2 = email_2.strip().lower()
print(clean_mail_2)
if email_3 is None:
    clean_email_3 = 'missing'
elif email_3.strip() == "":
    clean_email_3 = 'empty'
else:
    clean_email_3 = email_3.strip().lower()
print(clean_email_3)
if email_4 is None:
    clean_mail_4 = ('missing')
elif email_4.strip() == "":
    clean_mail_4 = ('empty')
else:
    clean_mail_4 = (email_4.strip().lower())
print(clean_mail_4)
```
## Zadanie 12
```python
file_name = " orders_2026_10_10.JSON "
clean_file_name = file_name.strip()
print(clean_file_name)
lower_file_name = clean_file_name.lower()
print(lower_file_name)
beggining_file_name = lower_file_name.startswith('orders')
print(beggining_file_name)
ending_file_name = str(beggining_file_name).endswith('json')
print(ending_file_name)
```
## Zadanie 13
```python
file_name = "orders_2026-10-12_PL.csv"
name_of_source = file_name[0:6:1]
print(name_of_source)
date_of_file = file_name[7:17:1]
print(date_of_file)
country_of_file = file_name[18:20:1]
print(country_of_file)
extension_of_file = file_name[21:25:1]
print(extension_of_file)
file_info = {
    'name_of_source' : name_of_source,
    'date_of_file' : date_of_file,
    'country_of_file' : country_of_file,
    'extension_of_file' : extension_of_file
}
print(file_info)
last_three_signs = file_name[21:25:1]
print(last_three_signs)
second_sign = file_name[::2]
print(second_sign)
reversed_name = file_name[::-1]
print(reversed)
```
## Zadanie 14
```python

```
