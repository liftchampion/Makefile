# Makefile

**Репозиторий является лишь демонстрацией примера Makefile, который я использую в своих С-проектах**  

Фичи:  
+ Мейкфайл сам находит .c-файлы  
+ Автосоздание зависимостей  
+ Объектные файлы и файлы зависимостей помещаются в отдельные папки  
+ Ничего лишнего не перекомпилируется  
+ Докомпилирует `libft` при необходимости
+ Автосоздание author-файла (необходим по правилам школы)
+ Автосоздание .gitignore
+ Возможность легко добавлять необходимые флаги для линковки/компиляции
+ Возможность компиляции с санитайзером, c флагом `-g` вместо `-Wall -Wextra -Werror`, с флагом оптимизации:  
  `make sanitize` `make debug` `make optimize`  
+ Возжность компиляции без графической библиотеки: `make novis`
+ Возможность проверки всех файлов на соответсвие *[Norminette code style](https://github.com/liftchampion/Norminette)*  

*С помощью данного Makefile компилируется проект [lem_in](https://github.com/liftchampion/lem_in)*
