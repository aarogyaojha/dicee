Sure! Here's a refined and polished version of your `README.md` with minor improvements for clarity, consistency, and professional presentation:

---

# 🎲 Dicee - A Dice Rolling App

Dicee is a fun and simple Flutter app where you can roll two dice by tapping on either of them. Each tap generates a random number between 1 and 6 and updates the dice face images accordingly.

## 📱 Screenshot

<p align="center">
  <img src="images/app.jpg" alt="Dicee Preview" width="300"/>
</p>

## 🚀 Features

- 🎲 Two interactive dice  
- 🔁 Random dice face generation (1–6)  
- 👆 Tap either dice to roll both  
- ✨ Clean, minimal UI with smooth interaction  

## 🛠️ Built With

- [Flutter](https://flutter.dev/)  
- Dart  
- Stateful widgets for interactivity  
- `Random` class for logic  
- `Image.asset` for displaying dice images  

## 📂 Project Structure

```
lib/
├── main.dart         # Main app logic and UI
images/
├── dice1.png
├── dice2.png
├── dice3.png
├── dice4.png
├── dice5.png
├── dice6.png
└── app.jpg           # Screenshot
```

## 📦 Asset Configuration

Ensure you declare your image assets in the `pubspec.yaml` file:

```yaml
flutter:
  assets:
    - images/
```

## 💡 How It Works

- The app uses `Random().nextInt(6) + 1` to generate numbers between 1 and 6.  
- Dice images are dynamically loaded using the format: `images/dice{number}.png`.  
- Tapping on either dice triggers a `setState()` call to update the UI with new random values.

## 🏁 Getting Started

1. **Clone the repository**  
   ```bash
   git clone https://github.com/aarogyaojha/dicee.git
   cd dicee
   ```

2. **Install dependencies**  
   ```bash
   flutter pub get
   ```

3. **Run the app**  
   ```bash
   flutter run
   ```

## 🙌 Credits

Inspired by the **Dicee App** concept from [The App Brewery](https://appbrewery.com)'s Flutter Bootcamp.

## 📄 License

This project is open-source and free to use under the [MIT License](LICENSE).
