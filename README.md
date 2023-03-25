![Screenshot 2023-03-20 200114](https://user-images.githubusercontent.com/90374083/226333460-54ed17d8-e019-4e6c-ba7a-436dce5c042f.jpg)

# Food Ordering App 🛎️
<a href="https://github.com/Qayyum1999"><img alt="views" title="Github views" src="https://komarev.com/ghpvc/?username=Qayyum1999&style=flat-square" width="125"/></a>

A fullstack Food Ordering App made in Flutter with Firebase, EmailJS.


## Features 🚀
1. Menu item selection.
2. Add item to your cart.
3. Make QR payment (TODO: add payment API).
4. Sync order list & bills to Kitchen App.
5. Print reciept & email e-reciept

## Built With 🛠
- Flutter (https://flutter.dev/) - UI toolkit for building beautiful, natively compiled applications for mobile, web, desktop, and embedded devices from a single codebase.
- flutter_dotenv (https://pub.dev/packages/flutter_dotenv) - A package for loading environment variables from a .env file.
- provider (https://pub.dev/packages/provider) - A package for managing app state and dependencies in Flutter.
- fluttertoast (https://pub.dev/packages/fluttertoast) - A package for showing toast messages in Flutter.
- cloud_firestore (https://pub.dev/packages/cloud_firestore) - A package for accessing and managing data in Firestore, a NoSQL cloud database by Firebase.
- firebase_core (https://pub.dev/packages/firebase_core) - A package for initializing and configuring Firebase services.
- firebase_storage (https://pub.dev/packages/firebase_storage) - A package for storing and retrieving files in Firebase Cloud Storage.
- cached_network_image (https://pub.dev/packages/cached_network_image) - A package for caching images from network URLs in Flutter.
- flutter_exit_app (https://pub.dev/packages/flutter_exit_app) - A package for exiting the Flutter app.
- email_validator (https://pub.dev/packages/email_validator) - A package for validating email addresses in Flutter.
- pdf (https://pub.dev/packages/pdf) - A package for creating PDF documents in Flutter.
- emailjs (https://pub.dev/packages/emailjs) - A package for sending email messages from Flutter using EmailJS services.
- path_provider (https://pub.dev/packages/path_provider) - A package for accessing the device's file system in Flutter.
- intl (https://pub.dev/packages/intl) - A package for internationalizing Flutter apps.
- nonce (https://pub.dev/packages/nonce) - A package for generating random nonces in Flutter.
- rsa_encrypt (https://pub.dev/packages/rsa_encrypt) - A package for encrypting and decrypting data using RSA encryption in Flutter.
- qr_flutter (https://pub.dev/packages/qr_flutter) - A package for generating QR codes in Flutter.

## Structure for app 🗼

    lib # Root Package

    ├── model                        #source of data
    |   ├── database            #all firebase functions (firestore,cloud storage)
    |
    ├── providers                    #state management
    |   
    ├── screens                      #ui screen for each pages 
    |   ├── home
    |   ├── menu
    |   ├── cart
    |   ├── billing
    |   ├── paymethod
    |   ├── qr payment
    |   ├── payment successful
    |   
    |                            
    └── main.dart                    #entry point

## Platform Supported 💻📱

- [x] Android
- [x] Web
- [x] iOS

![Screenshot 2023-03-20 210117](https://user-images.githubusercontent.com/90374083/226346500-1a728bd8-4c1e-47b3-be9b-66dc161278d9.jpg)


