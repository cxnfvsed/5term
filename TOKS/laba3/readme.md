# Написать программу, эмулирующую проверку кадров кодом Хэмминга. 


# Требования к наполнению программы: 
1. Программа должна быть написана на основе программы, относящейся
к лабораторной работе №1. 
2. Сохранить систему ввода-вывода сообщений, но допускать ввод
только символов 0 и 1 (как в лабораторной работе №2). 
3. Из сообщений формировать условные кадры (кодовые слова). Кадры
должны быть фиксированной длины. Длина одного кадра должна быть равна
сумме десяти и номера соответствующего студента по списку(23 + 5 контрольных битов). 
4. Предусмотреть возможность случайного искажения случайных битов. 
Вероятность искажения одного бита должна составлять 50 %, а вероятность
искажения двух битов должна составлять 20 %. 
5. Исходные данные для кода Хэмминга: код должен обнаруживать
двойные ошибки и исправлять одиночные. 
Требования к интерфейсу программы: 
1. В окно статуса необходимо выводить информацию о кодировании. 
Информацию выводить на стороне приемника. При этом одна строка должна
соответствовать одному кадру сообщения. В начале строки отображать
содержимое кадра с выделением (например, красным цветом) искаженных
битов. Далее, через разделитель (например, двоеточие), отображать код
Хэмминга (так же в виде символов 0 и 1).