# Imprint

A simple image editor for Android and iOS. Pick a photo, add text on top of it, style the text, and save the result to your gallery.

## Features

- Pick an image from the gallery
- Add multiple text layers on the image
- Drag each text layer anywhere on the image
- Bold and italic text
- Increase or decrease font size
- Change text color
- Align text left, center or right
- Add or remove line breaks in the text
- Long-press a text layer to delete it
- Save the edited image to the phone's gallery

## Tech Stack

- Flutter and Dart
- `image_picker` to choose a photo
- `screenshot` to capture the edited image
- `image_gallery_saver` and `permission_handler` to save it to the gallery

## Project Structure

```
lib/
  models/     TextInfo, the data for one text layer
  screens/    Home screen (pick image) and edit screen (canvas)
  widgets/    Edit logic (view model), text widget, button
  utils/      Permission helper
```

## Getting Started

```bash
flutter pub get
flutter run
```
