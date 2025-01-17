# Budget-planning

### [Ссылка на гугл колаб](https://colab.research.google.com/drive/1tT4PD1GnIyAwUwrsj9OE5w16l8eckE-w?usp=sharing "Данный блокнот содержит весь код программы с комментариями автора")

### [Ссылка на видео](https://drive.google.com/file/d/1y7uriKByNWadSoscDywe-ABxtnNXcnaJ/view "Видео с презентацией проекта")

### Описание:

Этот проект представляет собой программу для анализа и управления личным бюджетом. Она помогает пользователям отслеживать доходы и расходы, а также визуализировать их в виде графиков и диаграмм. Программа позволяет добавлять транзакции с указанием суммы, категории и описания, а также сохранять данные в Excel для дальнейшего использования.

Основные возможности программы:
- Ввод и сохранение транзакций (доходов и расходов).
- Категоризация транзакций для лучшего анализа.
- Просмотр сводной информации о бюджете (доходы, расходы, баланс).
- Визуализация данных в виде круговой и столбчатой диаграмм.
- Экспорт данных в формат Excel для дальнейшей работы.

Программа реализована в Google Colab, что позволяет запускать её без установки дополнительного ПО. Работать с программой можно в любой момент, имея доступ к интернету.

#### Требования:
- Google Colab (или любой другой инструмент для работы с Python).
- Установленные библиотеки: openpyxl, pandas, matplotlib.

#### Как использовать:
 1. Откройте ссылку на Colab.
 2. Запустите ячейку кода.
 3. Используйте текстовое меню для добавления транзакций, просмотра сводки и сохранения данных в Excel.
 4. Для визуализации графиков убедитесь, что у вас есть доступ к библиотеке matplotlib.

#### Структура программы:
 1. main() — основная функция, которая запускает программу и обрабатывает пользовательский ввод.
 2. add_transaction() — функция для добавления новых транзакций (доходов или расходов).
 3. view_summary() — функция для отображения сводной информации о бюджете.


 Пример вывода:
 
 Программа будет выводить текущие данные о бюджете:
 
- Общий доход: 50 000 руб.
- Общие расходы: 30 000 руб.
- Баланс: 20 000 руб.
- Расходы по категориям:
- Еда: 10 000 руб.
- Транспорт: 5 000 руб.
- Развлечения: 15 000 руб.

 4. save_to_excel() — функция для сохранения данных в файл Excel.

 Пример вывода:
[Ссылка на xls файл](https://github.com/aniekrnd/Budget-planning/raw/refs/heads/main/budget.xlsx)

 5. plot_charts() — функция для отображения графиков расходов и баланса.
  Пример вывода:
![Графики](https://github.com/aniekrnd/Budget-planning/blob/main/Графики.png)
