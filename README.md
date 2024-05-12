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

## ConstraintLayout

ConstraintLayout is a flexible layout manager that allows you to create complex layouts with a flat view hierarchy. In Jetpack Compose, ConstraintLayout is represented using the `ConstraintLayout` composable.

- To use ConstraintLayout, you need to add the ConstraintLayout dependency to your project. `implementation("androidx.constraintlayout:constraintlayout-compose:1.0.1")`

-  Then, you can create a ConstraintLayout and define constraints to position and size its children.

- ConstraintLayout in Jetpack Compose supports many advanced features, including chains, bias, barriers, groups, and more. These features allow you to create even more complex and responsive layouts.

## Simple Animations

- Animations are essential for creating dynamic and engaging user interfaces. Jetpack Compose provides simple and powerful tools for adding animations to your UI.

### Transition Animations

Transition animations are used to animate changes between different states of a UI element. In Jetpack Compose, transition animations can be achieved using the `animate*AsState` functions combined with modifiers like `Modifier.animateContentSize` or `Modifier.offset`.

### Value-based Animations

Value-based animations animate changes to a numeric value over time. In Jetpack Compose, value-based animations can be achieved using the animateValueAsState function.

- Jetpack Compose simplifies the process of adding animations to your UI, allowing you to create dynamic and visually appealing user experiences with ease.

For more information, refer to the official [Compose documentation](https://developer.android.com/jetpack/compose).

[Android Jetpack Compose Tutorial Playlist](https://www.youtube.com/playlist?list=PLQkwcJG4YTCSpJ2NLhDTHhi6XBNfk9WiC)

