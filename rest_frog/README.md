# rest_frog

A mason brick to create REST endpoints using Dart Frog.

## Usage 🚀

```
mason make rest_frog --endpoint todos
```

## Variables ✨

| variable           | description                  | default | type      |
| ------------------ | ---------------------------- | ------- | --------- |
| `endpoint`         | name of the endpoint         | todos   | `string`  |

## Output 📦

```
├── routes
│   └── todos
│        ├── [id].dart
│        └── index.dart
└── ...
```