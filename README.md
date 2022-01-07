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

![signIn](https://user-images.githubusercontent.com/35939405/148576125-bbb8f197-e0ec-41b0-a311-d6922786b3f8.png)
![reasons](https://user-images.githubusercontent.com/35939405/148576156-11c38f38-6171-470f-a1d5-3155d7efbbcb.png)
![confirmation](https://user-images.githubusercontent.com/35939405/148576167-9a16923f-0390-4d96-8364-4e5b12da68c4.png)
![networkError](https://user-images.githubusercontent.com/35939405/148576178-356c7dfb-dc8f-4d49-9076-0dc2dd75e3bd.png)
