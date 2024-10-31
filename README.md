# SwiftUI Image Picker Example

This project demonstrates how to use SwiftUI and `PHPickerViewController` to select and display images from the device's photo library in an iOS app. It includes features to show a selected image on the screen and provides a button to reset the view by removing the displayed image.

## Features

- **Select Image**: Users can tap a button to open the device's photo library and select an image.
- **Display Image**: The selected image appears on the screen, scaled to fit within a frame.
- **Remove Image**: An "X" button overlays the displayed image, allowing users to remove it and return the view to its initial "No image selected" state.

## Project Structure

- **ContentView**: The main SwiftUI view, displaying the button to open the image picker, the selected image, and the "X" button to remove the image.
- **PhotoPicker**: A `UIViewControllerRepresentable` wrapper for `PHPickerViewController`, handling image selection from the photo library.

## How to Use

1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/your-username/swiftui-image-picker-example.git
   cd swiftui-image-picker-example
   ```

2. **Run in Xcode**:
-	Open the project in Xcode.
-	Select an iOS simulator or a physical device.
-	Run the app.

3. **Usage**:
-	Tap the camera button to open the photo library.
-	Select an image to display it on the screen.
-	Tap the X button in the top-right corner of the image to remove it.

## Requirements

- iOS 15.6+
- Xcode 16.1+
- Swift 6.0.2+

## License

This project is licensed under the MIT License. See the LICENSE file for details.
