# Android Jetpack Compose

This repository contains educational code snippets for Android Jetpack Compose.

## Rows, Columns & Basic Sizing

- **Column**: Use the `Column` composable to create a vertical layout. Items are arranged from top to bottom.

- **Row**: Use the `Row` composable to create a horizontal layout. Items are arranged from left to right.

- **Sizing**: Adjust the size of components using sizing properties like `width`, `height`, and `weight`.

## Modifiers

- Modifiers are used to change the behavior, appearance, and layout of components.
  
- Customize your components using sizing, layout, appearance, and animation modifiers.

## Creating an Image Card Composable

An image card component typically consists of the following elements:

- **Image**: The main focal point of the card, usually a visual representation.
- **Title**: A title associated with the image.
- **Description**: A brief description providing context about the image.
  
This component combines these elements to present the image along with relevant text to the user.

## Styling Text

The "Styling Text" section explains how to format text in Jetpack Compose. 

- We utilize the Text component to achieve this. 

- This component offers a range of properties that allow us to customize text with attributes such as `color`, `size`, `font`, `weight`, `style`, `alignment` and `decoration`.

## State

State is a fundamental concept in Jetpack Compose that represents the current snapshot of data in your UI. 

- In Jetpack Compose, UI components are driven by state, and any change in state triggers a recomposition of the UI, updating it to reflect the new state.

- In Compose, state can be represented using the `remember` and `mutableStateOf` functions. `remember` is used to create a stable reference to an object that survives recompositions, while `mutableStateOf` is used to create a state holder that can be updated.

## Textfields

- Textfields are components that allow users to input text. In Jetpack Compose, textfields are represented by the `TextField` composable. The `TextField` composable is used to collect text input from users and dynamically update the input field.

## Buttons

- Buttons are components that allow users to initiate a specific action. In Jetpack Compose, buttons are represented by the Button composable. The Button composable waits for user clicks and listens for click events.

## Displaying Snackbars

- Snackbars are components used to display temporary notifications to users. In Jetpack Compose, snackbars are displayed using the SnackbarHost and Snackbar composable.

## Lists

Lists are commonly used to display a collection of items in a scrollable vertical layout. In Jetpack Compose, lists are represented using the `LazyColumn` composable for vertically scrolling lists and the `LazyRow` composable for horizontally scrolling lists.

### Vertical Lists

Vertical lists, represented by the `LazyColumn` composable, are used to display items in a vertical arrangement that can be scrolled vertically.

### Horizontal Lists

Horizontal lists, represented by the `LazyRow` composable, are used to display items in a horizontal arrangement that can be scrolled horizontally.
  
For more information, refer to the official [Compose documentation](https://developer.android.com/jetpack/compose).

[Android Jetpack Compose Tutorial Playlist](https://www.youtube.com/playlist?list=PLQkwcJG4YTCSpJ2NLhDTHhi6XBNfk9WiC)

