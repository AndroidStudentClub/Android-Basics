# Выходим в сеть. Retrofit, JSON, GSON, Picasso
✅Учимся делать сетевый запросы и получать ответ от сервера.

## В результате:

- Изучите основы работы c Retrofit, GSON, JSON, Picasso

### 🎯 Цели домашнего задания:

В этом задании мы отработаем навыки работы с Retrofit. Вы изучите основы работы с Gson, Retrofit и Picasso

### 👨Пользовательский сценарий:

Я как пользователь хочу увидеть список доступных рецептов

### 📚 Задание:

Создать сетевой запрос для получения списка рецептов. Отобразить полученные рецепты в RecyclerView в SearchFragment. Использовать Picasso для отображения картинок рецептов

Последовательность шагов:

- Добавить в AndroidManifest разрешение для доступа в Internet
- Добавить необходимые библиотеки (Retrofit, GSON, Picasso) в build.gradle.kts
- Создать модель данных, которая используется как модель ответа от сервера
- Описать возможные HTTP - методы. Метод Get **/recipes**
- Создать класс Retrofit.Builder — экземпляр, который использует интерфейс и API Builder, чтобы задать метод для операций HTTP.
- Базовый URL https://61e46d241a976f00176ee4a1.mockapi.io/api/v1/ для Retrofit
- Вызвать необходимый метод
- Создать UI (RecyclerView и ячейки) для отображения списка рецептов

### 📚 Полезные материалы:

- [Json to Kotlin Converter](https://jsonformatter.org/json-to-kotlin)
- [Текстовый туториал по работе с Retrofit](https://androidschool.ru/courses/android-retrofit-and-gson/)
- Базовый URL https://61e46d241a976f00176ee4a1.mockapi.io/api/v1/
- [Примеры кода из презентации](https://github.com/AndroidStudentClub/NetworkExamples/tree/master)


