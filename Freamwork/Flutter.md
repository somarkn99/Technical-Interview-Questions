# Flutter Interview Questions
1. How many types of widgets are there in Flutter?
    <br>
There are two types of widgets:
- StatelessWidget : A widget that does not require mutable state. 
- StatefulWidget: A widget that has mutable state.
    <br>
    <br>
2. What is an App State?
    <br>
- State that is not ephemeral, that you want to share across many parts of your app, and that you want to keep between user sessions, is what we call application state (sometimes also called shared state).
- Examples of application state: - User preferences - Login info - Notifications in a social networking app - The shopping cart in an e-commerce app - Read/unread state of articles in a news app
    <br>
    <br>
3. What is the `pubspec.yaml`  file and what does it do?
    <br>
- The `pubspec.yaml` file allows you to define the packages your app relies on, declare your assets like images, audio, video, etc.
- It allows you to set constraints for your app.
- For Android developers, this is roughly similar to a `build.gradle` file.
