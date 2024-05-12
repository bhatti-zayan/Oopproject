C++ Social Network Application
This is a command-line based social network application implemented in C++ using object-oriented programming (OOP) principles and dynamic memory allocation. The application simulates core social networking features like posting, commenting, liking, sharing memories, and managing friends/pages.

Features
User Profiles: Users can create profiles, add friends, and view/manage their own posts.
Pages: Pages can be created by users to share content with a wider audience.
Posts: Users and pages can share text posts (with optional images) and include activities like feelings, thoughts, or celebrations.
Likes: Users can like posts from friends and pages.
Comments: Users and pages can comment on posts.
Memories: Users can share posts as memories with added context.
Home Feed: Users can view a feed of recent posts from their friends and liked pages.
User/Page Views: Users can view the profiles of other users and pages.
Technical Details
Object-Oriented Design: The application follows OOP principles, with classes for User, Page, Post, Comment, Activity, and Memory.
Dynamic Memory Allocation: std::vector (dynamic arrays) are used to manage collections of objects, ensuring efficient memory usage.
File Storage (Optional): User and page data can be optionally stored in text files for persistence between sessions.
Unique Post IDs: Posts are assigned unique IDs for identification and reference.
How to Use
Compile: Use your preferred C++ compiler to compile the source files (e.g., g++ *.cpp -o SocialNetworkApp).
Run: Execute the compiled application (e.g., ./SocialNetworkApp).
Follow Menu Prompts: The application will guide you through creating users, pages, and interacting with various features.
Project Structure
include: Header files (.h) for class declarations.
src: Source files (.cpp) for class implementations.
data: (Optional) Text files for storing user and page data.
Dependencies
A C++ compiler (e.g., g++, Clang, Visual C++)
Standard C++ Library (no external libraries required)
Future Enhancements
Privacy Controls: Add options for public, friends-only, or custom post visibility.
Groups: Allow users to create and join groups for focused discussions.
Events: Enable users to create and share events.
Notifications: Implement a system for notifying users about new posts, comments, and likes
