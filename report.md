### Задание 2. 

1. Создать файл с несколькими строками текста
```bash
  echo -e "Сегодня отличный день.\nНадеюсь, тебе понравится этот день.\nДень был просто замечательный." > myfile2.txt
```
2. Использовать команду команду grep с флагом -in
```bash
grep -in "день" myfile2.txt
```

Результат
```
1:Сегодня отличный день.
2:Надеюсь, тебе понравится этот день.
3:День был просто замечательный.
```

### Задание 3.
1. Создать файл :
```bash
echo -e "Это строка с числом 12345.\nЭто строка без числа.\nА здесь 67890." > numbers.txt
```
2. Используйте команду grep с регулярным выражением для поиска всех строк, содержащих числа:
```bash
grep -E "[0-9]+" numbers.txt 
```

Результат
```
Это строка с числом 12345.
А здесь 67890.
```
