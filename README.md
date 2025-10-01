# spacehub-website

1. Початок роботи
 - Клонувати проект (один раз):
   git clone https://github.com/юзер/SpaceHubWeb.git
   cd SpaceHubWeb
 - Налаштувати дані (один раз):
   git config --global user.name "Ваше ім'я"
   git config --global user.email "ваш.email@example.com"

2. Щоденний робочий процес
 - Оновлюємо головну гілку master:
   git checkout master
   git pull origin master
 - Створюємо гілку під задачу:
   git checkout -b feature/назва-задачі

3.Вносимо зміни -> зберігаємо:
   git add .
   git commit -m "Короткий опис змін"
  
4.Відправляємо гілку на ГітХаб:
   git push -u origin feature/назва-задачі
   
5. На GitHub створити Pull Request в master.


4. Після злиття PR
 - Перейти на master:
   git checkout master
   git pull origin master
 - Видалити локальну гілку:
   git branch -d feature/назва-задачі
