# PVA2 - Programování a vývoj aplikací
## Cvičení 04: Datové struktury: Slovník

### 1
Vytvořte slovník zaměstnanec, který bude mít klíče křestní jméno `name`, příjmení `surname`, příjem `salary`

### 2
Ve slovníku zaměstnanec navyšte zaměstnanci mzdu o 6%

### 3 
Do slovníku employees přidejte pomocí vhodných operací zaměstnance z předchozích úkolů. Pokud máte 

```
employees = {
    'emp1' = {'name' = 'John', 'surname' = 'Doe', 'salary' = '32000'},
    'emp2' = {'name' = 'Emma', 'surname' = 'Phillips', 'salary' = '28000'}
}
```
### 4
Zobrazte hodnoty zaměstnance s klíčem `emp2`

### 5
Napište program, který přejmenuje klíč `city` na `location` v slovníku `emp_selected`
```
emp_selected = {
  "name": "Maria",
  "age": 34,
  "salary": 47000,
  "city": "Prague"
}
```

`Očekávaný výstup: {'name': 'Maria', 'age': 34, 'salary': 47000, 'location': 'Prague'}`

### 6
Ze slovníku `emp_selected` odstraňte klíče `age` a `salary` 

### 7
Vypočítejte průměr bodů v seznamu grades
```
grades = {
'Czech': 85,
'Chemistry': 67,
'History': 73,
'Economics': 88,
'Physics': 64,
'Computer Science': 91,
'Mathematics': 71
}
```

### 8
Ze seznamu `grades` zobrazte pomocí adekvátní funkce všechny získané body. Hodnoty uložte do samostatného seznamu (ne slovníku).

### 9
Pro slovník `grades` zobrazte pomocí adekvátní funkce seznam hodnocených předmětů. Hodnoty uložte do samostatného seznamu (ne slovníku).

### 10
Pomocí vhodných funkcí a seznamů z předchozích dvou cvičení zkombinujte nový slovník, který bude ve tvaru "předmět: body" 