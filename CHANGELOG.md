## 0.8.2

- Made `userChanges` and `authStateChanges` fire `null` on startup when signed out.
- Turned `userChanges` and `authStateChanges` into broadcast streams so they can be listened to more than once.
- Added `providerData` in MockUser. Thanks [kornperkus](https://github.com/kornperkus)!

## 0.8.1
- Implemented `FirebaseAuth.userChanges`. Thanks [mazzonem](https://github.com/mazzonem)!
- Implemented `User.updateDisplayName`. Thanks [oudehomar](https://github.com/oudehomar)!
- Implemented `FirebaseAuth.fetchSignInMethodsForEmail`. Thanks [ketanchoyal](https://github.com/ketanchoyal)!

## 0.8.0

- Updated dependency to firebase_auth ^3.0.0.
- Implemented `User.reload()`.

## 0.7.1

- Implement User.metadata. Thanks [mazzonem](https://github.com/mazzonem)!

## 0.7.0

- Removed dependency to Mockito.
- Updated dependency to firebase_auth ^1.3.0.

## 0.6.0

- Migrated to null safety. Thanks [YusufAbdelaziz](https://github.com/YusufAbdelaziz)!
- Updated dependency to firebase_auth ^1.0.1. Thanks [zariweyo](https://github.com/zariweyo)!

## 0.5.2

- Typed the arguments of `MockUser`'s constructor. Thanks [YusufAbdelaziz](https://github.com/YusufAbdelaziz)!

## 0.5.1

- Support for `signInWithPhoneNumber`.

## 0.5.0

Breaking change:

- Require supplying a `MockUser` instead of returning 'Bob'. Thanks [PieterHartzer](https://github.com/PieterHartzer)!

Refer to README.md on how to use it.

## 0.4.0

- Updated dependency to firebase_auth ^0.20.0+1. Thanks [Aanu1995](https://github.com/Aanu1995)!

## 0.3.2

- Support the newer `authStateChanges()` on top of the deprecated `get onAuthStateChanged`. Thanks [gallrein](https://github.com/gallrein)!

## 0.3.1

- Support `User.isAnonymous`.
- Support `User.email`.

## 0.3.0

- Support the breaking changes of firebase_auth 0.18.0+1.
- Removed `signInWithEmailAndLink` since it's not part of the API anymore.

## 0.2.1

- Added support for `signInAnonymously` and `signOut`. Thanks [shepeliev](https://github.com/shepeliev)!

## 0.2.0

- Upgraded firebase_auth dependency to ^0.16.0.

## 0.1.3

- Added support for `signInWithEmailAndPassword`, `signInWithEmailAndLink` and `signInWithCustomToken`.
- Documented supported features

## 0.1.2

- Implemented `MockFirebaseUser.getIdToken()`. Thanks [dfdgsdfg](https://github.com/atn832/firebase_auth_mocks/pull/2)!

## 0.1.1

- Upgraded firebase_auth dependency to ^0.15.2.

## 0.1.0

- Initial version.
