![Banner](https://via.placeholder.com/800x200.png?text=Shivay00001%2Flib)

# Shivay00001/lib

A lean Flutter/Dart library packaged with Docker and automated GitHub Actions CI for consistent builds and deployments.

## About

`lib` provides a minimal, production-ready scaffold for Flutter packages. It includes linting rules (`analysis_options.yaml`), containerization (`Dockerfile`), and continuous integration (`.github/workflows/flutter-ci.yml`) so you can focus on code, not plumbing.

## Installation

```bash
git clone https://github.com/Shivay00001/lib.git
cd lib
flutter pub get
```

Or build with Docker:

```bash
docker build -t shivay-lib .
```

## Usage

Run the app locally:

```bash
flutter run
```

Or run via container:

```bash
docker run --rm shivay-lib
```

## CI / CD

GitHub Actions workflow (`flutter-ci.yml`) runs on every push to validate builds and maintain code quality.

## License

See repository for details.