# Multithreaded Download Manager#

A Java Swing-based desktop application that downloads multiple files simultaneously using multithreading while displaying real-time progress for each download.

## Overview

This project demonstrates the use of Java Swing for GUI development, multithreading for concurrent task execution, networking for downloading files from the internet, and file handling for storing downloaded files locally.

Each file is downloaded in a separate thread, allowing multiple downloads to run simultaneously without freezing the user interface.

## Features

- Download multiple files concurrently
- Real-time progress tracking using progress bars
- Start and Stop download controls
- Responsive GUI using Java Swing
- Automatic file saving in a local downloads folder
- Thread interruption support for cancelling downloads
- Simple and user-friendly interface

## Technologies Used

- Java
- Java Swing
- Multithreading
- Networking (URL, URLConnection)
- File Handling (FileOutputStream)
- Event Handling

## Project Structure

```
RealDownloadManagerGUI.java
downloads/
README.md
```

## How It Works

1. The user clicks the **Start** button.
2. A separate thread is created for each file download.
3. The application connects to the file URL.
4. Data is downloaded in chunks and saved locally.
5. Progress bars update in real time.
6. When the download finishes, the status changes to **Completed**.
7. The **Stop** button interrupts all running download threads.

## Screenshots

You can add screenshots of the application here after running it.

## Learning Outcomes

This project helped in understanding:

- Java GUI development using Swing
- Thread creation and management
- Concurrent programming concepts
- Network communication in Java
- File input and output operations
- Event-driven programming

## Future Enhancements

- Pause and Resume functionality
- Download speed monitoring
- User-defined download URLs
- Download history tracking
- Dark mode interface
- Error recovery and retry mechanism

## How to Run

### Compile

```bash
javac RealDownloadManagerGUI.java
```

### Run

```bash
java RealDownloadManagerGUI
```

## Requirements

- Java JDK 8 or higher
- Internet connection

## Author

Rishank Gupta

## License

This project is developed for educational and learning purposes.
