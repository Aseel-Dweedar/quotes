# quotes

Include a method `getQuote()` that Use the file recentquotes.json to show random popular book quotes. The app showing one quote each time and showing the quote and the author when it is run.

### install dependencies and run the app

**To add the dependency** :

add this statement in the build.gradle like this:

```java
 dependencies {
  implementation 'com.google.code.gson:gson:2.8.7'
}
```

**Run the app** :

Chose run and the app should print one random quote and its uther.

**Teat the app** :

You can test the app from intlliJ by run the written test. or you can run it by using `./gradlew test`.

# Potent Quotables

Include a method `apiQuotes()` that make a request to an API to get a random quote. show this random quote. add it to json file of quotes, for use if the app goes offline in the future

**Run the app** :

Chose run and the app should print one random quote from Api and add it to json file `addQuote`.

**Teat the app** :

You can test the app from intlliJ by run the written test. or you can run it by using `./gradlew test`.
