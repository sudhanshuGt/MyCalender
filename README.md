﻿
# Calendar App
## Overview
The Calendar app is built using Kotlin and Jetpack Compose, designed to help users manage their tasks efficiently. It provides a calendar view, task management features, and seamless navigation between months.

## Features
- **Calendar View:** Display the current month's calendar, navigate between months, and select specific dates.
- **Task Management:**  Add, view, and delete tasks associated with specific dates.
- **Swipe Gestures:** Navigate between months using swipe gestures.
- **Theming:** Supports both dark and light themes with proper theme switching.
- **User ID Management:** Assigns a unique user ID to manage user-specific tasks.

## Design Patterns and Architecture
- **MVVM (Model-View-ViewModel):** Separates UI code from business logic, making the codebase more maintainable and testable.
- **Clean Architecture:** Divides the app into layers (Presentation, Domain, and Data) to enhance separation of concerns and improve testability.
- **Dependency Injection with Hilt:** Manages dependencies and simplifies the process of dependency injection.
- **Retrofit for API Calls:** Handles network requests efficiently and cleanly.

## APP LINK

[Download the app](https://github.com/sudhanshuGt/MyCalender/blob/main/apk_file/app-debug.apk)

## VIDEO LINK

[Watch the video](https://drive.google.com/file/d/1SBfFRdaWlmRJbuIIBOgpW1rfkaV3f6Pr/view?usp=sharing)

## Code Structure
- **Presentation Layer:** Contains UI-related components built using Jetpack Compose, including the main activity, composables, and view models.
- **Domain Layer:** Contains use cases that encapsulate the business logic.
- **Data Layer:** Contains data models and repositories for managing data sources, including network and local storage.
