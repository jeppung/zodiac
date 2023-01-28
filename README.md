<!--
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/guides/libraries/writing-package-pages).

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-library-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/developing-packages).
-->

A Flutter package to get zodiac from date

## Features

- returning zodiac as a String
- for now, function argument only support :
    - YYYY-MM-dd (ISO 8601) string format
    - YYYY-MM-DD hh:mm:ss string format

## Usage
Example:
```dart
const zodiac = Zodiac().getZodiac('2000-01-01');

const zodiac2 = Zodiac().getZodiac('2000-08-17 00:00:00');

print(zodiac); // Capricorn
print(zodiac2); // Leo
```

## Additional information

This is an open source package, feel free to contribute
