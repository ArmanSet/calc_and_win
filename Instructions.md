h (help) — вывести все доступные команды pdb.
l (list) — вывести в терминал по пять строк до и после строки, на которую интерпретатор указывает в данный момент.
s (step) — выполнить строку, на которую указывает интерпретатор в данный момент, и остановить выполнение программы на следующей строке, если это возможно.
n (next) — эта команда очень похожа на команду step, но она будет выполнять программу не строго по шагам. Команда next не станет заходить внутрь функций, а выполнит их целиком, в один шаг.
b (break) имя_файла:номер_строки — указать место обязательной остановки выполнения программы. Место обязательной остановки программы разработчики называют «точка останова» или «брейкпоинт».
c (continue) — выполнять программу до тех пор, пока она не отработает полностью или пока её выполнение не будет прервано ошибкой. Также выполнение этой команды будет прервано достижением точки останова — брейкпоинта.
p имя_переменной — вывести текущее значение переменной в терминал.
q (quit) — остановить работу отладчика.