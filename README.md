# Flutter Product API App

A simple Flutter application that fetches product data from a REST API and displays it in a beautiful grid layout.

## Features

* Fetch data from REST API
* Display products in GridView
* Show product image, title, and price
* Loading indicator while fetching data
* Clean and responsive UI

##  API Used

* https://fakestoreapi.com/products

##  Tech Stack

* Flutter
* Dart
* HTTP package
* REST API

##  Dependencies

Add this in your `pubspec.yaml`:

```yaml id="h21kda"
http: ^1.2.0
```
### Prerequisites

* Flutter SDK installed
* Android Studio / VS Code
* Emulator or physical device

## How It Works

* Uses `http` package to fetch data from Fake Store API.
* `json.decode()` converts API response into Dart list.
* `GridView.builder` displays products dynamically.
* `setState()` updates UI after data is loaded.
* Shows loading indicator until data is fetched.

## Future Improvements

* Add product detail page
* Implement search and filter
* Add shopping cart functionality
* Improve UI with animations
* Handle API errors gracefully

##  Author

**Mahek Prajapati**
