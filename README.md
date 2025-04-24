# BlogClub - News Application

BlogClub is a modern news application built with Flutter, providing users with personalized news feeds, categories, and story features.

## Features

- **Home Screen**:
  - User profile summary
  - Trending stories carousel
  - News categories filter
  - Latest news articles list
    ![1](https://github.com/user-attachments/assets/866b09b5-87ef-4397-8365-6367980b5d7a)


- **Article Screen**: 
  - Full article view with rich formatting
  - Related articles suggestions
  - Bookmark/save functionality
    ![2](https://github.com/user-attachments/assets/94ab88f3-396a-4f8b-bcf0-39d4aa9afcde)


- **Profile Screen**:  
  - User information management
  - "My Posts" section for saved/created content
  - Reading history
    ![3](https://github.com/user-attachments/assets/6c70209d-43ac-4fa2-831d-ebaf46266bea)


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
lib/
├── core/
├── features/
│   ├── article/
│   ├── home/
│   ├── profile/
│   └── shared/
├── app.dart
└── main.dart

---  

### Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss proposed changes.

### License  
MIT © 2023 BlogClub
