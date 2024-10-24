The main solution is the NetworkOfLibraries_DataBaseDiagram.drawio file
The repository also contains a png file with a simplified version of the database.

I have provided a variant in which different books have different rental rates, rather than a single price tag. The table with prices calculated on time stamps, so you can display discounts, warn about the imminent rise in the price of renting a particular edition based on the previous price. And also allows you to conveniently calculate the profit for a certain period of time.

From the obvious, the database can be enhanced by adding to the table “BooksInLibraries”: 
  1) A field responsible for the location of the book in the library, if necessary;
  2) An additional attribute responsible for whether the book is currently available (to minimize access to the BooksTookedByVisitors table when it is necessary to check whether the book is in the library). This flag could also be used for reservations or when moving a book from one library branch to another.
At this stage, I don't see the need for it.


<--------------------------------------------------- UA --------------------------------------------------->

Основним рішенням є файл NetworkOfLibraries_DataBaseDiagram.drawio
Репозиторій також містить png-файл зі спрощеною версією бази даних.

Я надав варіант, в якому різні книги мають різну вартість прокату, а не єдиний цінник. Таблиця з цінами вираховується за часовими мітками, тому можна відображати знижки, попереджати про швидке подорожчання прокату того чи іншого видання, виходячи з попередньої ціни. А також дозволяє зручно підрахувати прибуток за певний період часу.

З очевидного, базу даних можна вдосконалити, додавши в таблицю «BooksInLibraries» 
  1) Поле, що відповідає за місцезнаходження книги в бібліотеці, якщо це необхідно;
  2) додатковий атрибут, що відповідає за те, чи доступна книга в даний момент (щоб мінімізувати доступ до таблиці BooksTookedByVisitors, коли необхідно перевірити, чи є книга в бібліотеці). Цей флаг також може бути використаний для резервування або при переміщенні книги з однієї філії бібліотеки до іншої.
На даному етапі я не бачу в цьому необхідності.
