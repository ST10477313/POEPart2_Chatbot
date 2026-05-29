# Cybersecurity Chatbot Assignment

## Assignment Overview
- Developed a chatbot application in C# using WPF.
- Purpose was to demonstrate basic programming concepts and apply them in a practical system.
- Focused on cybersecurity awareness by providing predefined answers to common questions.
- Implemented sentiment detection to respond to emotions such as frustrated, happy, sad, or angry.
- Used file handling to store usernames and user interests.

## Features
- Greets new and returning users by checking `user_name.txt`.
- Stores topics users are interested in inside `interested_topic.txt`.
- Responds to cybersecurity-related keywords such as phishing, malware, password safety, safe browsing, firewall, VPN, hacked account, and fraud.
- Provides varied responses by randomly selecting from a pool of predefined answers.
- Filters out filler words using an ignore list.
- Displays chatbot and user messages in a WPF interface.

## Technical Details
- Written in C# with WPF for the user interface.
- Uses `ArrayList` to store replies and ignored words.
- Uses `File.AppendAllText` and `File.ReadAllLines` for persistence.
- Uses `Random` to select different responses.
- Handles exceptions such as `ArgumentOutOfRangeException` when collections are empty.

## Learning Outcomes
- Practiced event-driven programming in WPF.
- Applied object-oriented programming concepts in C#.
- Learned how to manage user input and match it against predefined responses.
- Gained experience with file I/O operations for saving and retrieving data.
- Debugged runtime errors and improved logic for keyword matching.
- Understood how simple rule-based chatbots can be implemented without external libraries.

## Project Structure
- `MainWindow.xaml.cs` handles user interface events and chatbot logic.
- `respond.cs` stores predefined answers and ignored words.
- `App.xaml.cs` manages application startup.
- `Part2.slnx` and `Part2.csproj` are solution and project files.
