# SimpleRateLimit

This is a simple rate limiting library for managing API requests.

## Installation

```xml

<dependency>
    <groupId>io.evest</groupId>
    <artifactId>simple-rate-limiter</artifactId>
    <version>0.0.3</version>
</dependency>
```

```gradle
implementation("io.evest:simple-rate-limiter:0.0.3")
```

## Usage

```kotlin
  Any()
    .tryBucket("1", 2, Duration.ofSeconds(1))
    .{ e ->
        ...
    }
```

## Configuration

## License

