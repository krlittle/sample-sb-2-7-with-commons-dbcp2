# sample-sb-2-7-with-commons-dbcp2

Saves and lists reminders on a pooled data source.

## Stack

- Spring Boot 2.7.18
- Java 17
- Gradle 8.4
- Commons DBCP2 2.9.0

## Build

```
./gradlew build
```

## Run

```
./gradlew bootRun
```

```
curl -X POST 'localhost:8080/reminders?message=call%20mom'
curl localhost:8080/reminders
```
