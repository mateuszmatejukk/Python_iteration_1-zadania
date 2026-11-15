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
