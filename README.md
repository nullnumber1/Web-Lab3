# MiSPI-Lab3
Написать сценарий для утилиты <i>Apache Ant</i>, реализующий компиляцию, тестирование и упаковку в jar-архив кода проекта из лабораторной работы №3 по дисциплине "Веб-программирование".

Каждый этап должен быть выделен в отдельный блок сценария; все переменные и константы, используемые в сценарии, должны быть вынесены в отдельный файл параметров; MANIFEST.MF должен содержать информацию о версии и о запускаемом классе.

<b>Cценарий должен реализовывать следующие цели (targets):</b>

1.  compile – компиляция исходных кодов проекта.
2.  build – компиляция исходных кодов проекта и их упаковка в исполняемый jar-архив. Компиляцию исходных кодов реализовать посредством вызова цели compile.
3.  clean – удаление скомпилированных классов проекта и всех временных файлов (если они есть).
4.  test – запуск junit-тестов проекта. Перед запуском тестов необходимо осуществить сборку проекта (цель build).
5.  xml – валидация всех xml-файлов в проекте.
6.  env – осуществляет сборку и запуск программы в альтернативных окружениях; окружение задается версией java и набором аргументов виртуальной машины в файле параметров.
