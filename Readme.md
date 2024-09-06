# OnlineTest - Java Quiz Application

This project is a simple online quiz application developed using Java Swing. It features a basic graphical user interface (GUI) to present multiple-choice questions and track user responses. The application also includes functionality for bookmarking questions and displaying the final result.

## Features

- **Multiple Choice Questions**: The quiz includes 10 questions with four options each.
- **Next Button**: Navigate through the questions.
- **Bookmark Button**: Bookmark the current question to revisit it later.
- **Result Button**: View the final score after completing the quiz.

## Screenshots

![Screenshot](screenshot.png)  
*(Replace `screenshot.png` with an actual screenshot of the application)*

## Requirements

- Java Development Kit (JDK) 8 or higher
- An IDE or a text editor to run the Java application

## How to Run

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/OnlineTest.git
   ```

2. **Navigate to the Project Directory**

   ```bash
   cd OnlineTest
   ```

3. **Compile the Java Code**

   ```bash
   javac OnlineTest.java
   ```

4. **Run the Application**

   ```bash
   java OnlineTest
   ```

## Code Overview

The application extends `JFrame` and implements `ActionListener` to handle user interactions. Here is a brief overview of the key components:

- **Labels and Radio Buttons**: Used for displaying questions and options.
- **Buttons**: Includes "Next", "Bookmark", and "Result" buttons.
- **ButtonGroup**: Groups radio buttons to allow only one selection at a time.
- **Action Handling**: Manages navigation between questions, bookmarking, and displaying results.

## Example

To understand how the application works, here's a brief description of its behavior:

1. **Navigating Questions**: Click the "Next" button to move to the next question. The application keeps track of the user's answers and updates the question and options accordingly.
2. **Bookmarking Questions**: Click "Bookmark" to save the current question for later review. Bookmarked questions can be revisited by clicking the corresponding bookmark button that appears on the interface.
3. **Displaying Results**: After answering all questions or clicking "Result", the application displays the total number of correct answers in a dialog box.

## Contributing

Feel free to fork the repository and submit pull requests. Contributions to improve the application or add new features are welcome.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Java Swing for providing the GUI framework.
- [Your Inspiration](https://example.com) for the original concept.

---
