Flashcard Quiz App 

-The Flashcard Quiz App is a native Android application designed as a personal study tool to help users create, manage, and test their knowledge on custom sets of flashcards. It provides a simple, clean, and efficient mobile-first experience. 

-Core Features and Modules: 

-Flashcard Management (CRUD): The app provides full Create, Read, Update, and Delete functionality. Users can add new cards with a question and answer, edit existing cards to correct or update information, and delete cards they no longer need. All cards are displayed in a scrollable list on the main screen. 

-Quiz Mode: A core learning feature that allows users to test themselves. The app retrieves all saved flashcards, shuffles them for a unique session every time, and presents them in a timed quiz. Users receive immediate feedback on whether their answer was correct and are shown the correct answer if they make a mistake. 

-Data Persistence: User-created flashcards are stored locally on the device using a built-in SQLite database. This ensures that all data is saved and available even after the app is closed and reopened. 

-Intuitive User Interface: The app features a modern UI with a BottomAppBar and FloatingActionButton for primary actions, making navigation clear and accessible. It also includes helpful user-centric features like an "empty state" message that guides new users when no flashcards have been created. 

-Technical Stack: 

-Platform: Native Android. 

-Language: Kotlin. -UI/Layouts: XML (eXtensible Markup Language) is used to define all layouts. Key components include RecyclerView for creating efficient lists, MaterialCardView for styling list items, and CoordinatorLayout with a BottomAppBar for a modern UI structure. 

-Database: Android's native SQLite database, managed via a custom SQLiteOpenHelper class for all database operations (creating tables, inserting, querying, updating, and deleting data). 

-Architecture: The app follows a multi-activity architecture, separating concerns into MainActivity (for displaying the list), FlashcardAddActivity (for creating/editing), and QuizActivity (for the quiz).
