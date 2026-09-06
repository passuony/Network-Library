# Network Library

Android application for browsing and searching books using the Google Books API, with
saved favorites, a customizable user profile, and a reading-reminder notification feature.
Built independently using Jetpack Compose and MVVM architecture.

## Features

- Search books by title, author, or keyword via live Google Books API integration
- Browse book details with cover images (loaded via Coil)
- Save books to a Favorites list (persisted locally with Room)
- Editable user profile (name, job title, portfolio link) with settings stored via DataStore
- Set a preferred reading time — schedules a local reminder notification via AlarmManager

## Architecture

- **Pattern:** MVVM (Model-View-ViewModel)
- **UI:** Jetpack Compose, Navigation Compose, Material 3
- **Architecture Components:** ViewModel (lifecycle-viewmodel-compose), Room, DataStore Preferences
- **Networking:** Retrofit2 + Gson converter, with OkHttp logging interceptor for the
  Google Books API
- **Async:** Kotlin Coroutines
- **Image loading:** Coil (coil-compose)
- **Reminders:** AlarmManager for scheduled local notifications
- **Language:** Kotlin

## Tech Stack

Kotlin · Jetpack Compose · MVVM · Retrofit2 · OkHttp · Room · DataStore · Coil ·
Navigation Compose · Coroutines · Google Books API · AlarmManager

## Testing

JUnit, Espresso, and Compose UI Testing (androidTest)

## Setup

1. Clone the repo
2. Open in Android Studio
3. Run on an emulator or physical device (min SDK [24])

