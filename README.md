# CheckMe – Todo App

CheckMe is a feature-rich **To-Do List App** built with **Flutter**. It allows users to manage their tasks efficiently with a simple, intuitive interface. The app incorporates modern state management techniques using **Riverpod** and supports both **light** and **dark mode** themes.

## 📌 Objectives

- Practice working with lists and UI updates using `setState` and **Riverpod** state management.
- Build multiple screens and navigate between them.
- Get comfortable with layout widgets and user interactions.

## 🚀 Features

### 1. **Login Screen**
- **Email and Password Validation**: Ensure the email format is correct and password meets basic criteria.
- Users must log in with valid credentials before accessing the app.

### 2. **Home Screen (Todo Dashboard)**
- **Welcome Message**: Display the user's name and avatar.
- **Todo List**: Display a list of todos using a `ListView` widget with checkboxes.
- **Add Todo**: A floating action button opens a form to add new todos, including a title and optional description.
- **Mark as Done**: Todos can be marked as completed, with a strikethrough or faded style to indicate completion.
- **Delete Todo**: Long-press or swipe a todo to delete it from the list.

### 3. **Todo Details Page (Optional Advanced)**
- Tapping on a todo opens a detailed view showing the full description, creation date, and an option to edit the todo.

### 4. **Due Date**
- Users can set a due date for each todo.
- Display **“Overdue”** if the due date has passed.

### 5. **Search Todos**
- Add a search bar to help users quickly find todos by title or description.

### 6. **Todo Categories**
- Assign a category (e.g., “School”, “Personal”, “Urgent”) to each todo.
- Filter todos by category.

### 7. **State Management with Riverpod**
- Replaced traditional `setState()` with **Riverpod** for local and global state management.
- `Providers` and `StateNotifiers` are used for both screen-specific and shared state.
  
### 8. **Theme Switching**
- Switch between **light mode**, **dark mode**, or the **system default theme** based on user preferences.
  
## 📦 Packages Used
- `flutter_riverpod`: A modern state management solution for Flutter.
- `provider`: A wrapper around Riverpod for easier integration.
- `flutter_localizations`: Supports multiple languages.
- `intl`: For date and time formatting.
  
## ⚡ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Hugues6221394/Mobile-Programming-Flutter/tree/master/lib

2. **Navigate to the project folder**:

   ```bash
   cd CheckMe-Todo-App
   ```

3. **Install dependencies**:

   ```bash
   flutter pub get
   ```

4. **Run the app**:

   ```bash
   flutter run
   ```

## 🔨 Development

### Contributing

Feel free to fork the repo, make changes, and submit pull requests. Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a Pull Request

---

## 💬 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---


