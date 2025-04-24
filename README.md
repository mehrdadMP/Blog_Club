# BlogClub - News Application

BlogClub is a modern news application built with Flutter, providing users with personalized news feeds, categories, and story features.

![Group 1](https://github.com/user-attachments/assets/28895245-e14a-484d-8a7e-de7e1c8acea2)


## Features

- **Home Screen**:
  - User profile summary
  - Trending stories carousel
  - News categories filter
  - Latest news articles list

- **Article Screen**: 
  - Full article view with rich formatting
  - Related articles suggestions
  - Bookmark/save functionality
    


- **Profile Screen**:  
  - User information management
  - "My Posts" section for saved/created content
  - Reading history

## Installation

1. Ensure Flutter is installed (minimum v3.0.0)

#### **How to Run**  
1. Clone the repo:  
   ```bash
   git clone https://github.com/mehrdadMP/Blog_Club.git
   ```  
2. Install dependencies:  
   ```bash
   flutter pub get
   ```  
3. Run on emulator/device:  
   ```bash
   flutter run
   ```  

---

### **Why Flutter?**  
- **Cross-platform**: Works on Android, iOS, and web with a single codebase.  
- **Fast UI prototyping**: Hot reload for instant changes.  
- **Great for learning**: Master widgets, state management, and async operations.  

---

## Dependencies
- **cupertino_icons:** ^1.0.2
- **dotted_border**: ^2.0.0+1
- **flutter_svg**: ^2.1.0
- **smooth_page_indicator**: ^1.0.0+2
- **cached_network_image**: ^3.3.0

---

### Project Structure  
```
assets/ # Assets & fonts
lib/
├── core/ # Core utilities & constants
│ ├── constants/ # App constants & strings
│ ├── utils/ # Helper functions
│ └── widgets/ # Shared widgets
│
├── features/ # Feature modules
│ ├── article/ # Article display logic
│ ├── auth/ # authentication
│ ├── home/ # Home screen components
│ ├── onBoarding/ # onBoarding
│ ├── profile/ # User profile section
│ └── splash/ # Splash screen components
│
├── gen/ # Generated assets & fonts files
└── main.dart # App entry point
```
---  

### Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss proposed changes.

### License  
MIT © 2023 BlogClub
