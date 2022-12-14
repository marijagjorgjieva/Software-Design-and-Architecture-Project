# Краток опис на проект


Генералната идеја на нашата апликација е да ги земе потребните податоци од двајца корисници и да им го олесни процесот на наоѓање место за средба. Системот ќе прими податоци од отворен извор на API во JSON формат. Корисниците треба да изберат град каде што сакаат да се сретнат, потоа да изберат една од понудените категории во тој град и на крај ги внесуваат двете нивни локации. Локациите може да се внесуваат преку тастатура или со користење на локациски сервиси. Системот потоа ги филтрира местата по тагови и останува со најрелевантните. По процесот на филтрирање, системот потоа сортира кое од местата е најблиско до првиот и вториот корисник. Конечниот резултат ги набројува најсоодветните места за средба според избраната категорија и дадените локации. Апликацијата ќе биде достапна на корисниците како Веб апликација. Технологијата ќе биде имплементирана со користење на Java Programming Language.



## Функциски барања

- Системот треба да работи на JVM
- Системот треба да користи Geoapify places API
- Системот треба податоците да ги прими од JSON
- Системот ќе користи Pipe-and-Filter архитектура

 

## Нефункциски барања

- Системот треба да го опфати процесот на пребарување на места по тагови
- Системот да овозможува рангирање на местата по близина на постојна локација
- Системот да овозможува внес на постојна локација преку тастатура
- Системот да овозможува пронаоѓање на локација преку локациски сервиси
- Ситемот да овозможува сортирање на новите места по категории
