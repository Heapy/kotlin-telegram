# Kotlin FAQ

_FAQ for Telegram chat [@kotlin_start](https://t.me/kotlin_start)._

## 1. I want to learn Kotlin. Where should I start?

### 1a. Documentation.

If you are just starting, you should check official [docs](https://kotlinlang.org/docs/reference/). The reference is well-written and answers most of beginner questions. Often there are editable code samples which you can run from within the webpage.

Brief language [syntax overview](https://kotlinlang.org/docs/reference/basic-syntax.html) and useful [idioms](https://kotlinlang.org/docs/reference/idioms.html).

[Java libraries](https://kotlinlang.org/docs/reference/java-interop.html) usage.

Short [language review](https://developer.android.com/kotlin/learn) by Google.

### 1b. Books.

You can find comprehensive list of books [right at the site](https://kotlinlang.org/docs/books.html).

**Should I read the book?** Most probably not. Docs should be enough to kick-off.

**But I really want a book. Which one should I pick?** If you have an experience with Java [Kotlin in Action](https://www.manning.com/books/kotlin-in-action) is one of the best books out there.

**What if I don't have programming experience?** [Atomic Kotlin](https://www.atomickotlin.com/) should soon become available. Preview of the book is available [as a Stepik course](https://stepik.org/course/15001/promo). Part of the material is free.

**What about Android?** [Android Development with Kotlin](https://www.packtpub.com/application-development/android-development-kotlin) or [Kotlin for Android Developers](https://leanpub.com/kotlin-for-android-developers).

### 1c. MOOC.

**Kotlin**:

* For those who just start learning to program: [Atomic Kotlin](https://stepik.org/course/15001/promo) Stepic course mentioned above.
- For those who already know Java: [Kotlin for Java developers](https://www.coursera.org/learn/kotlin-for-java-developers) from Coursera.
- [Kotlin Bootcamp for Programmers](https://www.udacity.com/course/kotlin-bootcamp-for-programmers--ud9011) — Kotlin course by Google.

**Android**:

- [Developing Android Apps with Kotlin](https://www.udacity.com/course/developing-android-apps-with-kotlin--ud9012) — free course for starters in Android with Kotlin.
- [Android Kotlin Fundamentals](https://codelabs.developers.google.com/android-kotlin-fundamentals/) — big codelab on Kotlin for Android development.
- [Refactoring to Kotlin](https://codelabs.developers.google.com/codelabs/java-to-kotlin/) — hour-long codelab on refactoring existing app.
- [Using Kotlin Coroutines in your Android App](https://codelabs.developers.google.com/codelabs/kotlin-coroutines/) — hour-long codelab on how to use coroutines in Android app.

### 1d. Excercises.

_(You should also check ["MOOC"](#1c-mooc))_

You can install [Kotlin Educational Plugin](https://www.jetbrains.com/help/education/learner-start-guide.html?section=Kotlin%20Koans) and learn the language interactively.

Short interactive examples with descriptions can also be found at ["Kotlin by Example"](https://play.kotlinlang.org/byExample/overview) page. 

Tasks called **Kotlin Koans** are also available [online](https://play.kotlinlang.org/koans/overview). This is the great way to get your feet wet with Kotlin.

[play.kotl.in](https://play.kotlinlang.org/), [Scratch files](https://kotlinlang.org/docs/tutorials/quick-run.html#scratches) in IDE and [REPL](https://kotlinlang.org/docs/tutorials/quick-run.html#repl) in terminal are a great tools to experiment with small fragments of code.

## 2. Can I learn Kotlin without Java knowledge? Is Kotlin a good first programming language?

**Yes**. Kotlin is quite a good language to become a first one. Knowledge of JVM/Java is not mandatory from the beginning, but would be useful in future if you continue your path with Kotlin on JVM platform.

For example, if you are going to create Android apps, be ready to read Java from time to time and use Java libraries on the daily basis. You should invest at least some time to become acquainted with Java and JVM as soon as you learn Kotlin foundation.

Remember that despite you are going to work with [Kotlin standard library](https://kotlinlang.org/api/latest/jvm/stdlib/index.html), it uses Java classes under the hood on JVM-based platforms (Android, JavaFX, backend). For example, Kotlin collections are backed by specific Java implementations.

Knowledge and understanding is important overall, but is not mandatory **while you learn**.

## 3. Does Kotlin code has specific style guides?

Yes. Coding conventions are available [at kotlinlang.org](https://kotlinlang.org/docs/reference/coding-conventions.html). There is also Android style guide [at developer.android.com](https://developer.android.com/kotlin/style-guide).

## 4. I still have questions

**Do you know how to solve your problem in Java?**
Use [Java to Kotlin converter in IDEA](https://www.jetbrains.com/help/idea/converting-a-java-file-to-kotlin-file.html) and make the result more idiomatic manually.

**Do you want to share your code with others?**
Try to trim it down to [minimal reproducible example](https://stackoverflow.com/help/minimal-reproducible-example) showing your main issue and post it via [play.kotlinlang.org](https://play.kotlinlang.org/).

Make sure you've skimmed through the corresponding documentation section.

Still got questions? Ask:

- [forum](https://discuss.kotlinlang.org/).
- [Slack-chat](https://kotl.in/slack).
- Telegram-chat [@kotlin_start](https://t.me/kotlin_start). **Note that this is a chat on Kotlin, so questions on algorythms or programming unrelated to the language are off-topic** and can be left without any response.

**Examples of bad questions for Kotlin chat**:

- How do I create singleton in Kotlin? _(direct answer can easily be found in docs)_
- How do I implement binary search? _(the question is too general and is off-topic)_
- How do I create an Adapter for `RecyclerView` in Kotlin? _(same way as it's done in Java. The chat for Android-specific questions is here: [@android_ru](https://t.me/android_ru))_
