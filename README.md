This Flutter code builds a **Home Screen** with a **Bottom Navigation Bar** that has two tabs: 

1. **Home Tab**: Displays a list of posts fetched from an API. Users can search for specific posts using a **Search TextField**, which filters the displayed posts by title based on user input.
  
2. **Profile Tab**: Shows the user’s information (retrieved from Firebase), but without edit options. It includes a **Logout Button** that logs the user out of Firebase and navigates them back to the login screen, clearing the session.

### Key Features:
- **BottomNavigationBar**: Allows navigation between the Home and Profile tabs.
- **FirebaseAuth**: Manages user session and enables the logout functionality.
- **API Integration**: Uses HTTP requests to fetch and display post data from an external API.
- **Search Filtering**: Allows real-time search of posts by title.
  
Overall, this code provides a structured, user-friendly screen layout that integrates both API data and Firebase authentication for an engaging and secure user experience.
