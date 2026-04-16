# TourGuide App

## Project Name: Bhopal Darshan

## Description

A Tour Guide Android App that presents relevant information to users visiting Bhopal — The City of Lakes, capital of Madhya Pradesh, India.

The app covers:
- 🏨 **Hotels** — Top-rated stays across the city
- 🍽️ **Restaurants** — Popular dining spots
- 📍 **Places** — Famous landmarks and attractions
- 🛍️ **Shopping** — Best malls and markets
- 🎉 **Events** — Local events and activities

## Tech Stack

- Language: **Java**
- Platform: **Android**
- Min SDK: As defined in `build.gradle`
- Architecture: Fragment-based with ViewPager + TabLayout

## Project Structure

```
app/
├── Activity/       → Splash, Main, Detail activities
├── Fragment/       → One fragment per category tab
├── Adapter/        → RecyclerView and Tab adapters
├── Model/          → Data models (Hotel, Place, Restaurant, etc.)
├── Data/           → Static data classes
└── Utils/          → Utility helpers
```

## How to Run

1. Clone this repository
2. Open in **Android Studio**
3. Let Gradle sync automatically
4. Run on an emulator or physical Android device

## Screenshots

> Add your screenshots here

## License

This project is open source under the [MIT License](LICENSE).
