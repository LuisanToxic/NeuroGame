  NeuroGame - Это тренажер для развития управления концентрацией с помощью шлема ЭЭГ NeuroPlay и программы NeuroPlayPro.
  В последние годы повышается интерес к разработкам интерфейса «мозг-компьютер» (ИМК), который обеспечивает взаимодействие человека с окружающим миром, минуя нервно-мышечные пути. В зарубежной литературе можно встретить синонимичное название мозго-машинные интерфейсы. 
  Развитие инвазивных и неинвазивных ИМК привело к созданию технологии, включающей множество разнообразных приборов, регистрирующих сигналы мозговой активности, а также программные средства для их обработки с конечной целью классификации состояний мозга или воображаемых команд, которые могут быть использованы для нейрореабилитации или нейроуправления. Системы нейрореабилитации на основе ИМК вселили надежду пациентам, страдающим двигательными нарушениями. Несколько исследовательских групп разработали технологии нейроуправления на основе ИМК, например, для управления инвалидными колясками, роботизированными руками, экзоскелетами и др. 
  Существует исследование в рамках аспирантской работы СПБПУ, основой которой является алгоритм подсчетов альфа и бета ритмов. Абстрактность математических результатов нуждается в визуализации через практическое применение. Один из подходов - применение этих результатов для управления игрой с ИМК.
  Цель моего проекта - создание игры-тренажера для развития управления концентрацией и медитацией для практического применения результатов исследования динамики изменения альфа и бета ритмов. 
  В процессе работы были поставлены следующие задачи: 
  ● Разработать игру «Лабиринт» на игровом движке Unity; 
  ● Создать графики для визуализации математических результатов обработки сигналов мозга; 
  ● Создать связь между математическими результатами и игрой с ИМК, используя процент концентрации для управления; 
  ● Протестировать возможность управления игрой с помощью ЭЭГ шлема. 
  С точки зрения основ нейробиологии, нас интересовала следующая теория: в лобных долях при умственной нагрузке начинают преобладать сигналы с частотами в пределах 14-30 Гц — так называемый, «бета-ритм». В затылочных долях, где находится зрительная кора, при расслаблении - возникает высокоамплитудный «альфа-ритм» в частотах 8-14 Гц. В частности, при закрытии глаз, когда мозгу не нужно обрабатывать обильные визуальные данные, этот эффект наиболее легко достижим и наблюдаем. 
  С помощью альфа и бета ритмов мы сможем определить процент концентрации и медитации. «Медитация» и «концентрация» - нормированные мета-показатели (0-100%), позволяющие понять, насколько человек в данный момент расслаблен или умственно загружен, соответственно. Создана игра-лабиринт с управляемой стрелочкой. Задача игрока – добраться до цели. Особенность игры заключается в том, что при уровне концентрации больше 50% стрелочка двигается по направлению, а если уровень концентрации меньше 50%, то стрелочка крутится по своей оси, тем самым позволяет выбрать направление. 
  Было проведено тестирование на нескольких студентах и сотрудниках колледжа и СПБПУ. По наблюдению, можно предположить, что контроль над концентрацией и медитацией можно повысить тренировками. Так, тестирование показало, что более опытные игроки проходят уровни быстрее. Из чего можно сделать вывод, что полученные с помощью игры навыки помогают повысить контроль над концентрацией в повседневной жизни и скрупулёзной работе. В дальнейшем, когда будет реализована возможность управления игры с помощью медитации (расслабления), при тренировке можно будет научиться расслабляться волевым усилием. 
  В результате, можно сделать следующие выводы: нами разработана игра «Лабиринт», которая представляет из себя случайно создаваемые уровни, размеры которых можно указать. Управление в игре реализовано с помощью одной кнопки и с помощью процента концентрации. 
  Была создана шкала для визуализации процента концентрации с динамическим обновлением в реальном времени. 
  Была реализована связь между игрой и математическими результатами с помощью API приложения «NeuroPlayPro» и движка Unity. 
  Было произведено тестирование управления игрой с помощью ЭЭГ шлема. В тестировании участвовала аспирантка СПБПУ Журавская А. 
  В процессе разработки все поставленные задачи были выполнены в полном объеме. В дальнейшем планируется реализовать дополнительное управление с помощью процента медитации (расслабления) с функцией переключения режимов, систему многопользовательского использования, сохранение результатов.
