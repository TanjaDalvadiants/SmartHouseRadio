# SmartHouseRadio
## CI, Maven, JaCoCo, Lombok
### «Объекты с внутренним состоянием, управление состоянием при тестировании. Lombok»
#### «Объектно-ориентированное программирование и проектирование»
Система "Умный дом", которая умеет:

> Требования к работе с радиостанциями:

* можно задавать количество радиостанций при создании объекта, по умолчанию — 10
* номер текущей радиостанции изменяется в пределах от 0 до количества радиостанций не включительно. То есть если станций 10, то номер последней — 9
* если текущая радиостанция — максимальная, и клиент нажал на кнопку next, следующая, на пульте, то текущей должна стать нулевая
* если текущая радиостанция — 0, и клиент нажал на кнопку prev, предыдущая, на пульте, то текущей должна стать максимальная
* присутствует сеттер текущей станции

> Требования к работе с уровнем громкости звука:

* клиент должен иметь возможность увеличивать и уменьшать уровень громкости звука в пределах от 0 до 100
* если уровень громкости звука достиг максимального значения, то дальнейшее нажатие на + не должно ни к чему приводить
* если уровень громкости звука достиг минимального значения, то дальнейшее нажатие на - не должно ни к чему приводить
