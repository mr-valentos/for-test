Принципи об'єктно-орієнтоване програмування

Прикладом об'єкту реального світу буде - акустична колонка
Клас колонок: потужність, кількість динаміків, підсилювач

Успадкувння: домашні колонки, студійні колонки, концертні колонкі

Поліморфізм: Є можливість відтворити пісню. Наприклад Майкла Джексона або Тіни Кароль.
 Принцип в тому, що як для першої так і для другої пісні використовується команда з
 одним іменем - відтворити пісню.

Інкапсуляція: Візмем той же метод відтворення пісні. Для його реалізації треба подати
 сигнал на підсилювач, потім передати сигнал на динаміки в яких діафрагма буде відтворювати
 звук. Але користувачу достатньо бачити що пісня відтворюється.

SOLID
-Принцип єдиного обов'язку (Single responsibility principle)
 Головна задача колонки відтворювати звук, і не потрібно вигадувати ще щось.
-Принцип відкритості/закритості (Open/closed principle)
 Можливо додати ще один динамік, але не можна змінювати принцип дії підсилювача.
-Принцип підстановки Барбари Лісков (Liskov substitution principle)
 Кожна колонка може виконати головну задачу відтворення звуку.
-Принцип розділення інтерфейсу (Interface segregation principle)
 Для звичайного користувача достатньо интерфейсу керуванням гучності, а для
 професіоналів можна добавити інтерфейс єквалайзеру.
-Принцип інверсії залежностей (Dependency inversion principle)
 Працездатність колонки не залежить від типу дінаміку.