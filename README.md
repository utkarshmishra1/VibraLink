# VibraLink

VibraLink is an iOS application designed to empower visually impaired users by converting text from PDFs and images into tactile feedback via custom Arduino gloves. The app utilizes SwiftUI for the user interface, Core Bluetooth for communication with the Arduino device, and various frameworks for text extraction.

## Features

- **PDF and Image Text Extraction**: Extracts text from PDFs and images using Vision and PDFKit frameworks.
- **Real-Time Document-to-Vibration Translation**: Converts extracted text into tactile feedback using a Braille mapping system.
- **Bluetooth Integration**: Establishes a seamless connection with custom Arduino gloves to transmit vibration patterns.

## Technologies Used

- **SwiftUI**: For building the user interface.
- **Core Bluetooth**: To connect and communicate with the Arduino device.
- **Vision and PDFKit**: For text extraction from images and PDFs.
- **Arduino**: For translating text into vibration patterns.

## Setup

### Prerequisites

- **Xcode**: Make sure you have the latest version of Xcode installed.
- **Arduino Setup**: You'll need an Arduino board with vibration motors set up as per the Braille mapping system.
