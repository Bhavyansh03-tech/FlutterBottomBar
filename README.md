# Bottom Navigation Bar Demo

This Flutter app demonstrates the use of a `BottomNavigationBar` to switch between different pages. The app features four pages: Home, Message, Settings, and Account, each with a label and icon.

## Features
- **Bottom Navigation Bar**: Allows users to navigate between four sections of the app.
- **Responsive UI**: Updates the page content based on the selected navigation item.
- Simple and clean design using Flutter's Material 3 theme.

## Preview
<img src="https://github.com/user-attachments/assets/0c981c80-8242-40b5-84a1-65ad57746a8d" alt="First Screenshot" style="width: 200px; height: auto; margin-right: 10px;">
<img src="https://github.com/user-attachments/assets/1e7c44a4-7cbd-41a9-8301-48fb1c5795ae" alt="Second Screenshot" style="width: 200px; height: auto;">

## Code Explanation

- **`MyApp` class**: The main widget that sets up the theme and the home page.
- **`MyHomePage` class**: A stateful widget that manages the navigation between pages using the `BottomNavigationBar`.
- **`_navigationBottomBar` method**: A function that updates the `_selectedIndex` to switch between pages when the user taps a navigation item.
- **`_pages` list**: Contains the content of each page—Home, Message, Settings, and Account—which is displayed based on the selected index.

### Main Components:
- **BottomNavigationBar**: Displays a fixed navigation bar with four items: Home, Message, Settings, and Account.
- **Center widget**: Shows the title of the current page in large font size to indicate which section is active.

## Getting Started

To run this project on your local machine:

1. Clone the repository and open it in your IDE:
   ```bash
   git clone https://github.com/Bhavyansh03-tech/FlutterBottomBar.git
   ```
2. Run the project on an emulator or a physical device.
   ```bash
   flutter run
   ```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

## Contact

For questions or feedback, please contact [@Bhavyansh03-tech](https://github.com/Bhavyansh03-tech) on GitHub or connect with me on [LinkedIn](https://www.linkedin.com/in/bhavyansh03/).

---
