# Holdable Button Flutter Plugin

**Holdable Button** is a Flutter plugin that allows you to create interactive buttons with a unique animation. It enables users to hold a button, displaying a loading animation along its border, and then triggering a callback once the animation completes.


## Demo 🎥

<img src="https://raw.githubusercontent.com/MahdiGharooni/holdable_button/master/assets/gifs/long.gif" alt="long">  <img src="https://raw.githubusercontent.com/MahdiGharooni/holdable_button/master/assets/gifs/icon.gif" alt="icon"> 


<img src="https://raw.githubusercontent.com/MahdiGharooni/holdable_button/master/assets/gifs/circle.gif" alt="circle"> <img src="https://raw.githubusercontent.com/MahdiGharooni/holdable_button/master/assets/gifs/oval.gif" alt="oval">

<img src="https://raw.githubusercontent.com/MahdiGharooni/holdable_button/master/assets/gifs/rectangle.gif" alt="rectangle"> <img src="https://raw.githubusercontent.com/MahdiGharooni/holdable_button/master/assets/gifs/square.gif" alt="square">



## Benefits 🚀

- **Interactive Animation**: Engage users with a button that responds to long presses, offering an interactive and visually appealing experience.

- **Customizable**: Tailor the button to match your app's design by adjusting parameters such as button color, loading color, border radius, child widget, animation duration, and start position.

- **User Engagement**: Encourage users to interact with your app by introducing a novel way to trigger actions.

## How to Use 🛠️

1. Add the Holdable Button plugin to your `pubspec.yaml` file:

    ```yaml
    dependencies:
      holdable_button: any
    ```

2. Install the plugin by running:

    ```bash
    flutter pub get
    ```

3. Import the package in your Dart code:

    ```dart
    import 'package:holdable_button/holdable_button.dart';
    ```

4. Implement the HoldableButton widget:

    ```dart
    HoldableButton(
      width: 300,
      height: 200,
      buttonColor: Colors.blue,
      loadingColor: Colors.white,
      radius: 15.0,
      child: Text('Hold Me'),
      duration: 5,
      startPoint: 0.25,
      onConfirm: () {
        // Callback when animation completes
      },
    )
    ```


## Customization ⚙️

The `HoldableButton` widget supports the following parameters:

- `buttonColor`: The color of the button.
- `loadingColor`: The color of the loading animation.
- `radius`: The border radius of the button.
- `child`: The widget inside the button.
- `duration`: The duration of the animation in seconds.
- `startPoint`: start position.
- `onConfirm`: Callback when the animation completes.

Feel free to experiment with these parameters to achieve the desired look and behavior.

## Contributing 🤝

Contributions are welcome! Please feel free to submit issues or pull requests.

