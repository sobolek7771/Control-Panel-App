# Тестовые задания для Инфогрейс

Все работает на SingleActivity через 2 NavigationControler:

1 - main_page_navigation для создания и добавления новых фрагментов на главный экран

2 - control_panel_navigation для работы с выезжающей панели управления
  
Создание миссии занимет много места, поэтому выезжающее меню справа реализовано через ViewPager, он занимает все пространство на экране что удобно при заполнении полей.

Все экраны отрисованы как в техническом задании, кнопки работают.

При проектировании архитектуры решил использовать реляционную базу данных(что оказалось ошибкой). Для корректного отображения миссии в MissionList необходимо было использовать нереляционную базу данных с json. Для решения проблемы ее необходимо переписать. Это займет у меня 2 дня, поэтому приложено то что сделано на данный момент.

Сделано за 6 дней.

По итогу прошу дать критику, это важно для меня. Спасибо
