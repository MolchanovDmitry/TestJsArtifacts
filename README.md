# TestJsArtifacts

```kotlin
./gradlew :module1:jsBrowserDistribution

```

Модуль `module1` зависит от модуля `common`. При генерации js-артефактов модуля `module1` включаются сущности из `common`.
Можно ли сгенерировать артефакты `module1` без сущностей модуля `common`?
