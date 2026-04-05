# iOS Diffable Data Source Demo

Modern iOS demo project showcasing Swift Diffable Data Source using `UITableViewDiffableDataSource` with async/await and Combine in a clean MVVM architecture.

## Features

- Diffable Data Source (UITableView)
- Async/Await concurrency
- Combine for state binding
- MVVM architecture
- Drag & Drop reordering
- Swipe to delete
- Dynamic list updates with smooth animations

## Why Diffable Data Source?

This approach is useful for:
- Managing dynamic lists
- Handling frequent data updates
- Simplifying complex UI state
- Avoiding manual `reloadData()` calls
- Getting automatic animations for free

## Architecture

- **MVVM**
- `ViewModel` handles business logic and state
- `Combine` binds state to UI
- `DiffableDataSource` manages UI updates

#Check out the app in action:

![App Demo](demo.gif)
