README for Simple Counter App

---
The **Simple Counter App** is a Flutter-based mobile application designed 
to demonstrate the fundamentals of building interactive user interfaces.
The app features a clean and intuitive design with a **blue-themed color scheme** with **interactive icon** as its central visual element. 
Users can interact with the app by pressing a button to increment a counter, which is displayed prominently in a styled container.

This project is ideal for beginners learning Flutter, as it covers essential concepts such as:
- **State management** using `StatefulWidget`.
- **Layout design** with `Column`, `Container`, and `Row`.
- **Styling** with `ThemeData`, `BoxDecoration`, and `TextStyle`.
- **Interactivity** with `ElevatedButton` and `setState`.

---

**Features**
1. **Blue-Themed UI**:
   - The app uses a consistent blue color scheme for the AppBar, icons, text, and buttons.
   - A light blue background with a blue border highlights the counter.

2. **Icon**:
   -  (using `Icons.directions_run` as a placeholder) adds a unique visual element to the app.

3. **Interactive Counter**:
   - Users can press the **Increment Counter** button to increase the counter value.
   - The counter is displayed in a styled container for better visibility.

4. **Responsive Design**:
   - The app is designed to work seamlessly on both Android and iOS devices.

3. **Run the App**:
   - Navigate to the project directory:
     ```bash
     cd simple-counter-app
     ```
   - Run the app using:
     ```bash
     flutter run
     ```

4. **Interact with the App**:
   - Tap the **Increment Counter** button to increase the counter value.
   - Observe the counter update in real-time.

 **Code Structure**
The project is organized as follows:
  **`main.dart`**: The entry point of the app. Contains the `MyApp` and `HomeScreen` widgets.
  **`MyApp`**: A `StatelessWidget` that sets up the app's theme and home screen.
  **`HomeScreen`**: A `StatefulWidget` that manages the app's state and UI. Includes:
  - A **icon**.
  - A **text message**.
  - A **counter display** in a styled container.
  - An **increment button**.

---

**Dependencies**
This project uses the following Flutter packages:
- **`material`**: Provides the core UI components and theming.

---
 **Customization**
To customize the app:
1. **Change the Icon**:
   - Replace the placeholder icon (`Icons.directions_run`) with a custom sword icon or image asset.

2. **Modify the Theme**:
   - Update the `primarySwatch` in `ThemeData` to change the app's color scheme.

3. **Add Animations**:
   - Use Flutter's animation libraries to add transitions or effects to the counter.

4. **Extend Functionality**:
   - Add features like a reset button or a decrement button for more interactivity.

---

#### **Contributing**
Contributions are welcome! If you'd like to contribute to this project:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Submit a pull request with a detailed description of your changes.

---

#### **License**
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---
 **Contact*
For questions or feedback, please contact:
- **Manahil Bashir**   
- **GitHub**: [https://github.com/ManahilBashir1/lab4_flutterwidget/new/main?filename=README.md]

---

Thank you for using the **Simple Counter App**!
