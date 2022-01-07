# StudentCheckinKiosk
SwiftUI iPad app that allows RIT students to swipe their ID card and check into a student queue to meet with an academic advisor. Used the latest APIs from WWDC2021 along with the new features introduced with Swift 5.5. 

Technologies used:
- SwiftUI 3
- Combine
- Swift 5.5 async / await network calls
- Multithreading
- UIKit (used for listening to card reader device which acts as a USB keyboard)

Features:
- Connection to USB card reader
- Error handling
- Automatically resets after a period of inactivity
