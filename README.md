
```markdown
# Custom Progress Indicator 🎨

A customizable progress indicator built using **Jetpack Compose** with smooth animations and a sleek design.

![New Gif](https://github.com/user-attachments/assets/04f4060c-0430-40d1-b656-c00f40d4ce12)



## Features ✨
- **Customizable size, colors, and text**: Adjust the component to fit your design.
- **Smooth animations**: Seamless transitions for indicator progress and color changes.
- **Lightweight and efficient**: Designed with performance in mind.
- **Reusable functions**: Easy to integrate into any Compose-based project.

## Preview 📸
A visual demonstration of the custom progress indicator:

![Screenshot 2024-12-25 203207](https://github.com/user-attachments/assets/224b576f-976d-4629-8c26-2721e09305e0)

```kotlin
CustomComponent(
    canvasSize = 300.dp,
    indicatorValue = 75,
    maxIndicatorValue = 100,
    backgroundIndicatorColor = Color.Gray,
    forgroundIndicatorColor = Color.Green,
    bigTextSuffix = "%",
    smallText = "Progress"
)
```

## How to Use 🚀
1. **Add the Component**:
   Import the `CustomComponent` composable function into your project:
   ```kotlin
   CustomComponent(
       canvasSize = 300.dp,
       indicatorValue = 50, // Current progress
       maxIndicatorValue = 100, // Maximum value
       forgroundIndicatorColor = Color.Blue, // Progress color
       backgroundIndicatorColor = Color.LightGray, // Background color
       bigTextSuffix = "GB",
       smallText = "Remaining"
   )
   ```
2. **Customize the Parameters**:
   - `canvasSize`: The size of the component (default: 300.dp).
   - `indicatorValue`: Current progress value.
   - `maxIndicatorValue`: Maximum value for the progress.
   - `backgroundIndicatorColor`: Color of the background arc.
   - `forgroundIndicatorColor`: Color of the progress arc.
   - `bigTextSuffix`: Suffix for the large text (e.g., "GB").
   - `smallText`: Label for the small text (e.g., "Remaining").

## Requirements 🛠️
- **Kotlin**: Version 1.8 or higher.
- **Jetpack Compose**: Version 1.5 or higher.
- **Android Studio**: Bumblebee or newer.

## Setup 🛠️
1. Clone this repository:
   ```bash
   https://github.com/mouad2008dev/rounded-indicator-jetpack-compose.git
   ```
2. Open the project in Android Studio.
3. Sync Gradle and run the project.

## Contributing 🤝
Feel free to fork this repository and submit pull requests! Any contributions to improve the design, performance, or features are welcome.

## Acknowledgments ❤️
- Built with ❤️ using Jetpack Compose.
- Inspired by modern UI/UX trends.

---

🌟 **Don't forget to star this repository if you found it useful!**
```
