Karaoke-System
This Karaoke System is a console-based application built using C++ that allows users to manage and interact with a personal music library. The system provides multiple features for users to add songs, search for specific tracks, view recently added and recently played songs, and even play songs in shuffle mode.

Features:

1. Add a Song: Users can input the song title, artist, and lyrics to add a new song to their library. The system stores this information and provides a success message upon completion.


2. View Library: The system displays all songs in the library, sorted alphabetically by song title. Users can select any song from the library to play and view the lyrics.


3. View Recent Added Songs: The system keeps track of the most recent songs added to the library. Up to 5 recent songs are shown, providing quick access to newly added music.


4. View Recent Played Songs: Similarly, the system tracks the most recent songs that have been played, showing the last 5 songs played in order of most recent.


5. Search for Songs: Users can search for songs in the library by entering keywords that may match the song title or artist name. The system then displays all matching songs.


6. Shuffle Mode: This feature allows users to play songs in a random order. The system shuffles the songs in the library and plays them one after the other, giving a dynamic experience to the user.


7. Input Validation: The system ensures that only valid choices are accepted for menu options. If an invalid input is entered (e.g., entering letters when a number is expected), the system prompts the user to re-enter a valid choice without crashing or behaving unexpectedly.



Design Considerations:

Song Storage: Songs are stored as objects in a vector. Each song has a title, artist, and lyrics as its properties.

Dynamic Song Library: The library grows as users add new songs, and it maintains recent actions (e.g., recent additions and plays).

Sorted Library: Songs are sorted alphabetically by title to help users easily browse their music collection.

Usability: The program is designed to be user-friendly, with clear instructions and robust input validation to prevent errors or crashes due to incorrect inputs.


Technologies Used:

C++: The program is written in C++, taking advantage of the Standard Template Library (STL) for dynamic data structures like vectors and functions for sorting and searching.

Basic Console I/O: All interaction is through the console, where the user inputs data and the system responds with prompts and outputs.


Purpose:

The project aims to showcase an interactive and user-friendly approach to managing and playing songs in a karaoke system. It's designed to handle a dynamic music library with added functionalities like recent song tracking, shuffle play, and search features. This project provides a foundation for building more complex music and media management systems.

This Karaoke System demonstrates key programming concepts, including object-oriented design, dynamic memory management, file handling, input validation, and sorting algorithms. It’s an excellent example of how C++ can be used to develop interactive applications with user-friendly interfaces.
