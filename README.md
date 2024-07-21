# 🎬 The Movie App

## Overview

The Movie App is an Android application that fetches the latest popular movies from [themoviedb.org](https://www.themoviedb.org/) and displays them in a clean and user-friendly interface. This app is built using modern Android development tools and libraries - Retrofit, Paging Library, MVVM architecture, Dagger Hilt for dependency injection, ViewBinding, and Glide for image loading.

## Features

- 📈 Fetches latest popular movies from themoviedb.org
- 📜 Infinite scrolling using Paging Library
- 🏗️ Clean MVVM architecture
- 💉 Dependency Injection with Dagger Hilt
- 🖼️ Efficient image loading with Glide
- 📲 Modern UI with ViewBinding

## Getting Started

### Prerequisites

- Android Studio (latest version)
- Gradle (latest version)
- An API key from [themoviedb.org](https://www.themoviedb.org/documentation/api)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/ANKUR2304/TheMovieApp.git
    cd TheMovieApp
    ```

2. Open the project in Android Studio.

3. Add your themoviedb.org API key 

4. Build and run the project.

## Architecture

This app is built using the MVVM (Model-View-ViewModel) architecture to separate concerns and ensure a clean codebase.

- **Model**: Handles data operations. This includes fetching data from the network using Retrofit and handling data from the repository.
- **View**: Displays the data and reacts to user interactions. This layer includes Activities and Fragments using ViewBinding.
- **ViewModel**: Acts as a bridge between the Model and View. It holds UI-related data that survives configuration changes.

## Libraries Used

- **Retrofit**: For making network requests to the MovieDB API.
- **Paging Library**: For efficient data pagination and infinite scrolling.
- **Dagger Hilt**: For dependency injection.
- **ViewBinding**: For view binding to avoid `findViewById` calls.
- **Glide**: For image loading and caching.
