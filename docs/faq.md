# Kotlin FAQ

_FAQ для Telegram-чата [@kotlin_start](https://t.me/kotlin_start)._

## 1. Хочу изучать Kotlin. Где начать?

### 1a. Документация.

Если вы начинающий — обратите внимание на официальную [документацию](https://kotlinlang.org/docs/reference/). Она хорошо написана и позволяет решить абсолютное большинство вопросов, возникающих при изучении языка. Как правило, на каждой странице есть редактируемые примеры кода, которые можно запустить прямо в браузере.

Краткий обзор [синтаксиса](https://kotlinlang.org/docs/reference/basic-syntax.html) языка и полезных [идиом](https://kotlinlang.org/docs/reference/idioms.html).

Про использование [Java-библиотек](https://kotlinlang.org/docs/reference/java-interop.html).

Очень краткий [обзор языка](https://developer.android.com/kotlin/learn) от Google.

Базового английского (на крайний случай Google Translate) достаточно для понимания документации. Но если русскоязычные материалы предпочтительнее — есть неофициальные [переводы](https://kotlinlang.ru/).
**Имейте в виду, что в отдельных случаях переводы могут быть устаревшими. Сверяйтесь с официальным сайтом языка.**

### 1b. Книги.

Большой список книг по Kotlin есть [на сайте](https://kotlinlang.org/docs/books.html).

**Нужна ли мне книга?** Скорее всего, нет. В большинстве случаев документации будет хватать.

**Но я хочу именно книгу — какую выбрать?** Если есть опыт на Java — берите [Kotlin in Action](https://www.manning.com/books/kotlin-in-action).

**А если у меня нет опыта программирования?** Скоро выйдет [Atomic Kotlin](https://www.atomickotlin.com/). Книга есть в раннем доступе в виде [курса на Stepik](https://stepik.org/course/15001/promo). Часть материалов доступна бесплатно.

**Для Android'a?** [Android Development with Kotlin](https://www.packtpub.com/application-development/android-development-kotlin) или [Kotlin for Android Developers](https://leanpub.com/kotlin-for-android-developers).

### 1c. Курсы.

**Kotlin**:

- Для тех, кто только начинает программировать — [Введение в язык Котлин](https://www.coursera.org/learn/vvedenie-v-yazyk-kotlin) на Coursera.
- Для тех, кто знает Java — [Kotlin для Java разработчиков](https://www.coursera.org/learn/kotlin-for-java-developers) на Coursera.
- [Kotlin Bootcamp for Programmers](https://www.udacity.com/course/kotlin-bootcamp-for-programmers--ud9011) — Kotlin курс от Google.

**Android**:

- [Developing Android Apps with Kotlin](https://www.udacity.com/course/developing-android-apps-with-kotlin--ud9012) — бесплатный курс для начинающих про разработку Android-приложений с использованием Kotlin.
- [Android Kotlin Fundamentals](https://codelabs.developers.google.com/android-kotlin-fundamentals/) — большой codelab по использованию Kotlin в контексте Android-разработки.
- [Refactoring to Kotlin](https://codelabs.developers.google.com/codelabs/java-to-kotlin/) — часовой codelab про рефакторинг существующего приложения.
- [Using Kotlin Coroutines in your Android App](https://codelabs.developers.google.com/codelabs/kotlin-coroutines/) — часовой codelab о том, где и как использовать корутины в приложении.

### 1d. Упражнения.

_(посмотрите также на раздел ["Курсы"](#1c-курсы))_

Установив [Kotlin Educational Plugin](https://www.jetbrains.com/help/education/learner-start-guide.html?section=Kotlin%20Koans), вы сможете ознакомиться с языком в интерактивном режиме.

Маленькие интерактивные примеры с обьяснениями можно также попробовать на странице ["Kotlin by Example"](https://play.kotlinlang.org/byExample/overview). 

Задачки, называемые **Kotlin Koans**, также доступны [онлайн](https://play.kotlinlang.org/koans/overview). Отличный инструмент для продолжения знакомства с языком.

Для написания небольших фрагментов кода иногда удобно использовать [play.kotl.in](https://play.kotlinlang.org/), [Scratch files](https://kotlinlang.org/docs/tutorials/quick-run.html#scratches) в IDE или [REPL](https://kotlinlang.org/docs/tutorials/quick-run.html#repl) в консоли.

## 2. Можно ли учить Kotlin, не зная Java? Подходит ли Kotlin как первый язык программирования?

**Да**. Kotlin вполне подходит как первый язык. Знание JVM/Java не обязательно на начальных этапах, но, вероятно, (если вы планируете использовать Kotlin на JVM-платформе) потребуется позже.

Например, если вы собираетесь писать приложения для Android — готовьтесь читать Java-код время от времени и очень часто использовать Java-библиотеки. Инвестируйте хотя бы немного времени в понимание Java и основ JVM как освоите базу языка Kotlin.

Примите во внимание, что хотя вы и будете работать со стандартной [библиотекой Kotlin'a](https://kotlinlang.org/api/latest/jvm/stdlib/index.html), на JVM-платформе (Android, JavaFx, backend) под капотом иногда используются Java-классы (например, конкретные реализации Java-коллекций скрыты за Kotlin-интерфейсами). 

Знание и понимание целевой платформы полезно в целом, но не обязательно на **начальных** этапах.

## 3. У Kotlin-кода есть какой-то особый стиль?

Да. Конвенции по оформлению кода есть [на сайте](https://kotlinlang.org/docs/reference/coding-conventions.html). Для Android'a также [тут](https://developer.android.com/kotlin/style-guide).

## 4. У меня остались вопросы / что-то непонятно.

**Знаете, как написать нужный вам код на Java?**
Используйте [конвертацию кода в IDEA](https://www.jetbrains.com/help/idea/converting-a-java-file-to-kotlin-file.html) и доведите до идиоматического Kotlin-кода вручную.

**Хотите показать код другим?**
Сократите его до [маленького примера](https://ru.stackoverflow.com/help/minimal-reproducible-example), демонстрирующего то, с чем возникли затруднения, и загрузите на [play.kotlinlang.org](https://play.kotlinlang.org/).

Убедитесь, что вы просмотрели соответсвующий раздел в документации (см. выше).

Все еще непонятно? Спросить можно:

- на [форуме](https://discuss.kotlinlang.org/).
- в [Slack-чате](https://kotl.in/slack).
- в Telegram-чате [@kotlin_start](https://t.me/kotlin_start). **УЧТИТЕ, что чат посвящен языку Kotlin и вопросы по алгоритмам или основам программирования (не языка) не соответствую тематике чата.** Подобное поведения будет рассматриваться как злоупотребление помощью и, скорее всего, вопросы останутся неотвеченными.

**Пример неуместных вопросов для Kotlin-чата**:

- Как мне создать singleton в Kotlin? _(прямой ответ есть в документации)_
- Как мне реализовать бинарный поиск? _(вопрос слишком общий или не соответствует тематике чата)_
- Как сделать Adapter в RecyclerView на Kotlin? _(так же, как и в Java. Чат для Android-вопросов есть тут: [@android_ru](https://t.me/android_ru))_
