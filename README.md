# flutter_tags

[![pub package](https://img.shields.io/badge/pub-0.1.0-orange.svg)](https://pub.dartlang.org/packages/flutter_tags)
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.me/dnag88)

An implementation of Selectable or Input tags.


## In your pubspec.yaml

```
dependencies:
  flutter_tags: "^0.1.0"
```


## Selectable Tags

```
    import 'package:flutter_tags/flutter_tags.dart';
    .
    .
    SelectableTags(
        tags: <Tag>[
            Tag(
                id:1,
                title: First Tag,
                active: true
            ),
            Tag(
                id:2,
                title: Second Tag,
                active: false
            ),
            .
            .
        ],
        columns: 3, // default 4
        onPressed: (tag){
            print(tag);
        },
    )
```


DEMO
---
![Demo 1](https://github.com/Dn-a/flutter_tags/)


## Input Tags

Work in Progress...



For help getting started with Flutter, view our online [documentation](https://flutter.io/).

For help on editing package code, view the [documentation](https://flutter.io/developing-packages/).