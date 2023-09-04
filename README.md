<a name="readme-top"></a>
[![wakatime](https://wakatime.com/badge/github/popoway/goknights.svg)](https://wakatime.com/badge/github/popoway/goknights) 
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/popoway/goknights)
![GitHub language count](https://img.shields.io/github/languages/count/popoway/goknights)
![GitHub last commit (branch)](https://img.shields.io/github/last-commit/popoway/goknights/main)

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/popoway/goknights">
    <img src="assets/icon/icon.png" alt="GoKnights logo" width="80" height="80">
  </a>

  <h3 align="center">GoKnights</h3>

  <p align="center">
    Your Queens College Knights experience, elevated
    <br />
    <a href="#readme-toc"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://testflight.apple.com/join/74kqoOhR" target="_blank">
      <img src="assets/docs/testflight-badge.png" alt="Available on Apple TestFlight" height="40">
    </a>
    <br />
    <a href="https://github.com/popoway/goknights">View Demo</a>
    ·
    <a href="https://github.com/popoway/goknights/issues">Report Bug</a>
    ·
    <a href="https://github.com/popoway/goknights/issues">Request Feature</a>
  </p>
</div>

## Table of Contents
<a name="readme-toc"></a>
- [Description](#description)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [Privacy](#privacy)
- [License](#license)
- [Disclaimer](#disclaimer)

## Description

Inspired by numerous inquiries and questions from incoming freshmen during new student orientation this summer, this app is created in order to serve as a centralized destination to showcase some of the highlighted student services and resources available on campus.

![Screen shot of home screen of goknights](./assets/screenshots/app_overview.jpg)

This project is currently under development and will be updated periodically.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

Below are some brief instructions on setting up this project locally. To get a local copy up and running follow these simple example steps.

### Prerequisites

* [Flutter SDK](https://flutter.dev/docs/get-started/install) for cross-platform development
* [Xcode](https://developer.apple.com/xcode/) and [CocoaPods](https://cocoapods.org/) for iOS dependencies
* [Android Studio](https://developer.android.com/studio) for Android dependencies
* Your preferred code editor (I use [Visual Studio Code](https://code.visualstudio.com/))

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/popoway/goknights.git
   ```
2. Install dependency packages
   ```sh
   flutter pub get
   ```
3. Enter your API keys in `.env`:
   ```
   # example .env file
   GOOGLE_MAPS_API_KEY=your_key_here
   UPLOAD_KEYSTORE_PASSWORD=google_play_keystore
   ```
4. You're all set! Run the app with `flutter run` or your preferred editor.

To generate a _release_ build for iOS without codesign, run the following command:
```
flutter build ios --release --no-codesign
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Roadmap

- [x] User onboarding with different roles -> views
- [ ] Injectable JS WKWebview for calendars
- [ ] i18n support with Italian, Chinese and Spanish

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you found a bug or have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".  
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Feel free to [open an issue](https://github.com/popoway/goknights/issues/new) for bug reports, and your suggestions on how this app can be improved.

Pull requests: If this is your first Flutter/Dart project, below are a few resources to get you started:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

To report a security vulnerability, please review the [Security Policy](https://github.com/popoway/goknights/blob/main/SECURITY.md).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Privacy

This app does not use cookies or similar technology to deliver its services and to analyze traffic. The app author respects your privacy. Please review the [Privacy Policy](https://github.com/popoway/goknights/blob/main/PRIVACY.md) for more information on how your data is handled.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License

[GNU General Public License v3.0](https://github.com/popoway/goknights/blob/main/LICENSE)

Permissions of this strong copyleft license are conditioned on making available complete source code of licensed works and modifications, which include larger works using a licensed work, under the same license. Copyright and license notices must be preserved. Contributors provide an express grant of patent rights.

Open Source Licenses and Acknowledgements are available within the "About" dialog of the app.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Disclaimer

"Disclaimer: While I am both an employee of Queens College and a graduate student in Computer Science here, the "GoKnights" app is a personal project developed during my summer break. The content, views, and opinions expressed within the app are solely my own and do not reflect the positions, strategies, or opinions of Queens College. This app is neither officially associated with nor maintained by Queens College as part of my employment."

<p align="right">(<a href="#readme-top">back to top</a>)</p>