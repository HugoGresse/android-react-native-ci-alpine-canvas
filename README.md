# Alpine React Native Android build image WITH Canvas & python support

[trucknet-io/android-react-native-ci-alpine](https://github.com/trucknet-io/android-react-native-ci-alpine) but with canvas dependencies python 2 installed. 

Perfect for a webdriver.io setup. 

---

### Pull from Docker Hub
| API level | Command | 
| --------- | ------- | 
| ❌Android 21 (5.0) | `docker pull trucknet/android-react-native-ci-alpine:android-21` 
| ❌Android 22 (5.1) | `docker pull trucknet/android-react-native-ci-alpine:android-22` 
| ❌Android 23 (6.0) | `docker pull trucknet/android-react-native-ci-alpine:android-23` 
| ❌Android 24 (7.0) | `docker pull trucknet/android-react-native-ci-alpine:android-24`
| ❌Android 25 (7.1) | `docker pull trucknet/android-react-native-ci-alpine:android-25` 
| ❌Android 26 (8.0) | `docker pull trucknet/android-react-native-ci-alpine:android-26`
| ❌Android 27 (8.1) | `docker pull trucknet/android-react-native-ci-alpine:android-27`
| ☑️Android 28 (9.0) | `docker pull hugogresse/android-react-native-ci-alpine-canvas:android-28`


### Use as Base Image
| API level | Command |
| --------- | ------- |
| ❌Android 21 (5.0) | `FROM trucknet/android-react-native-ci-alpine:android-21` |
| ❌Android 22 (5.1) | `FROM trucknet/android-react-native-ci-alpine:android-22` |
| ❌Android 23 (6.0) | `FROM trucknet/android-react-native-ci-alpine:android-23` |
| ❌Android 24 (7.0) | `FROM trucknet/android-react-native-ci-alpine:android-24` |
| ❌Android 25 (7.1) | `FROM trucknet/android-react-native-ci-alpine:android-25` |
| ❌Android 26 (8.0) | `FROM trucknet/android-react-native-ci-alpine:android-26` |
| ❌Android 27 (8.1) | `FROM trucknet/android-react-native-ci-alpine:android-27` |
| ☑️Android 28 (9.0) | `FROM hugogresse/android-react-native-ci-alpine-canvas:android-28` |
