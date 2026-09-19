# Cryptocurrency App

An Android application built with **Kotlin** and **Jetpack Compose** that displays cryptocurrency data using the CoinPaprika API. 

## Features
* View a list of active cryptocurrencies.
* View detailed information about a specific cryptocurrency, including its description, tags, team members, and current status.
* Built entirely using modern Android development practices and declarative UI.

## Tech Stack & Architecture
* **UI:** [Jetpack Compose](https://developer.android.com/jetpack/compose) for a declarative UI.
* **Architecture:** MVVM (Model-View-ViewModel) with Clean Architecture principles (Presentation, Domain, and Data layers).
* **Dependency Injection:** [Dagger Hilt](https://dagger.dev/hilt/).
* **Networking:** [Retrofit](https://square.github.io/retrofit/) & OkHttp for REST API communication.
* **Asynchronous Programming:** [Kotlin Coroutines](https://kotlinlang.org/docs/coroutines-overview.html) and Flow.
* **Navigation:** Jetpack Compose Navigation.

## API
This app uses the free [CoinPaprika API](https://api.coinpaprika.com/) to fetch cryptocurrency data.

## Getting Started
1. Clone this repository.
2. Open the project in **Android Studio**.
3. Build and run the app on an emulator or physical device. (No API key is required).
