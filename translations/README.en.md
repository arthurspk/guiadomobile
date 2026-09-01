<p align="center">
  <a href="https://github.com/arthurspk/guiadevbrasil">
    <img src="../images/guia.png" alt="Guia Dev Brasil" width="160" height="160">
  </a>
  <h1 align="center">Mobile Development Guide</h1>
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/arthurspk/guiadomobile?style=flat-square" alt="Stars">
  <img src="https://img.shields.io/github/forks/arthurspk/guiadomobile?style=flat-square" alt="Forks">
  <img src="https://img.shields.io/github/last-commit/arthurspk/guiadomobile?style=flat-square" alt="Last commit">
  <img src="https://img.shields.io/github/license/arthurspk/guiadomobile?style=flat-square" alt="License">
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square" alt="PRs Welcome">
</p>

> Complete mobile development guide: learning paths, courses, books, channels, tools and communities
> to get into the field and grow. Last review: September 2026.
>
> This is a translation of the Brazilian Portuguese guide. Resources are curated for the Brazilian community, so many are in Portuguese; 🇺🇸 marks English-language content.

## 🌍 Languages
[🇧🇷 Português](../README.md) · 🇺🇸 English (you are here)

## 📚 Table of contents
- [🎯 About this guide](#-about-this-guide)
- [🗺️ Roadmap](#-roadmap)
- [🚀 Where to start](#-where-to-start)
- [🎓 Free courses](#-free-courses)
- [💰 Paid courses](#-paid-courses)
- [📖 Documentation](#-documentation)
- [📚 Books](#-books)
- [🎥 YouTube channels](#-youtube-channels)
- [🎙️ Podcasts](#-podcasts)
- [📰 Sites, blogs and newsletters](#-sites-blogs-and-newsletters)
- [🛠️ Tools](#-tools)
- [🧪 Hands-on projects and challenges](#-hands-on-projects-and-challenges)
- [🤖 AI in practice](#-ai-in-practice)
- [📜 Certifications](#-certifications)
- [💼 Career and jobs](#-career-and-jobs)
- [👥 Communities](#-communities)
- [🚨 How to contribute](#-how-to-contribute)
- [📄 License](#-license)
- [💙 Support the project](#-support-the-project)

## 🎯 About this guide
**Mobile** development means building applications for phones and tablets — today, in practice, for **Android** and **iOS**, which together dominate the market. There are two paths: **native** (Kotlin + Jetpack Compose on Android; Swift + SwiftUI on iOS), which gives full access to the platform, and **cross-platform** (Flutter, React Native, Kotlin Multiplatform), where a single codebase produces apps for both systems. Brazil is one of the largest app markets in the world, and banks, fintechs, retail and startups hire for all of these stacks.

This guide is for people who want to enter the field or specialize. It covers the four main stacks starting from the **official documentation**, plus store publishing, AI in the workflow, certifications, salaries and jobs. **Portuguese and free** resources come first in every section; 💰 marks paid content, 🇺🇸 English-language content and 🆕 material published or updated between 2024 and 2026. Every link was verified on the date of the last review.

## 🗺️ Roadmap
- [roadmap.sh — Android Developer](https://roadmap.sh/android) — Community visual roadmap for native Android: Kotlin, Compose, architecture, testing and publishing. 🇺🇸
- [roadmap.sh — iOS Developer](https://roadmap.sh/ios) — Visual roadmap for iOS: Swift, SwiftUI/UIKit, persistence, networking and the App Store. 🇺🇸
- [roadmap.sh — Flutter](https://roadmap.sh/flutter) — Visual Flutter roadmap: Dart, widgets, state, packages and deployment. 🇺🇸
- [roadmap.sh — React Native](https://roadmap.sh/react-native) — Visual React Native roadmap: JavaScript/TypeScript, React, Expo, navigation and native modules. 🇺🇸
- [Android Developer Roadmap (skydoves)](https://github.com/skydoves/android-developer-roadmap) — Image-and-text roadmap maintained by a Google Developer Expert, with topics in priority order. 🇺🇸
- [iOS Developer Roadmap (BohdanOrlov)](https://github.com/BohdanOrlov/iOS-Developer-Roadmap) — iOS knowledge tree with links for every topic, from basics to advanced. 🇺🇸
- [Apple Developer Pathways](https://developer.apple.com/pathways/) — Apple's official learning paths (Swift, SwiftUI, App Store, design) that put docs, videos and tutorials in order. 🆕 🇺🇸
- [Learn Flutter (oficial)](https://docs.flutter.dev/learn) — Official page gathering the learning path, codelabs, videos and recommended courses for Flutter. 🇺🇸
- [Kotlin Multiplatform — recursos de aprendizado (oficial)](https://kotlinlang.org/docs/multiplatform/kmp-learning-resources.html) — JetBrains' official list of tutorials, samples and courses to learn KMP and Compose Multiplatform. 🆕 🇺🇸

**Summary path** (follow in order; each step has resources in the sections below):

1. **Fundamentals** — programming logic, Git, HTTP/JSON and **one** language: Kotlin (Android), Swift (iOS), Dart (Flutter) or JavaScript/TypeScript (React Native).
2. **Pick the platform** — native (Android or iOS) or cross-platform (Flutter, React Native, KMP). Don't try to learn everything at once: master one stack and switch later if you need to.
3. **Declarative UI** — Jetpack Compose, SwiftUI, Flutter widgets or React Native components: layout, lists, navigation, themes, dark mode and accessibility.
4. **State and architecture** — unidirectional data flow, ViewModel/`@Observable`/Riverpod/Zustand, dependency injection and layering (UI, domain, data).
5. **Data** — consuming REST APIs (Retrofit/Ktor, URLSession, dio, fetch), local persistence (Room, SwiftData, Drift, SQLite) and managed backends (Firebase, Supabase).
6. **Quality** — unit and UI tests, offline-first, performance, security (OWASP MAS) and permissions.
7. **Publishing** — signing, App Bundle/IPA, Google Play Console, App Store Connect, TestFlight, CI/CD (fastlane, Codemagic, GitHub Actions) and store policies.
8. **Advanced** — Kotlin Multiplatform and Compose Multiplatform, on-device AI (Gemini Nano, Foundation Models, LiteRT), monetization, analytics and native modules.

## 🚀 Where to start
1. **Pick a stack and look at the map.** Compare the [Android](https://roadmap.sh/android), [iOS](https://roadmap.sh/ios), [Flutter](https://roadmap.sh/flutter) and [React Native](https://roadmap.sh/react-native) roadmaps. No Mac? Start with Android, Flutter or React Native — building for iOS requires macOS.
2. **Learn the language before the framework:** [Tour of Kotlin](https://kotlinlang.org/docs/kotlin-tour-welcome.html), [Swift — Getting Started](https://www.swift.org/getting-started/), [Dart](https://dart.dev/language) or [JavaScript on MDN (Portuguese)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript). And [Git](https://git-scm.com/book/pt-br/v2) from day one.
3. **Install the environment:** [Android Studio](https://developer.android.com/studio?hl=pt-br), [Xcode](https://developer.apple.com/xcode/) (Mac only), the [Flutter SDK](https://docs.flutter.dev/install) or [Expo](https://docs.expo.dev/get-started/create-a-project/) for React Native.
4. **Try it without installing anything:** [Kotlin Playground](https://play.kotlinlang.org/), [Swift Playground](https://developer.apple.com/swift-playground/), [DartPad](https://dartpad.dev/) and [Expo Snack](https://snack.expo.dev/).
5. **Take your stack's official course:** [Android Basics with Compose (Portuguese)](https://developer.android.com/courses/android-basics-compose/course?hl=pt-br), [Develop in Swift Tutorials](https://developer.apple.com/tutorials/develop-in-swift/), the [Flutter learning pathway](https://docs.flutter.dev/learn/pathway) or the [Expo tutorial](https://docs.expo.dev/tutorial/introduction/).
6. **Complement with a course in Portuguese:** [Alex Felipe (Compose)](https://www.youtube.com/playlist?list=PLYaQbIm_3oZ9BwznyXn7n_Zl1KBq3I9oO), [Portal Hugo Cursos (Swift)](https://www.youtube.com/playlist?list=PLxNM4ef1BpxjjMKpcYSqXI4eY4tZG2csm), [Flutterando (Flutter)](https://www.youtube.com/playlist?list=PLlBnICoI-g-d-J57QIz6Tx5xtUDGQdBFB) or [DevClub (React Native + Expo)](https://www.youtube.com/watch?v=a8YvzTXft9c).
7. **Build two or three real apps** — a to-do list with persistence, a weather app consuming an API, a catalog with login — using [App Ideas](https://github.com/florinpop17/app-ideas) and the [Flutterando challenges](https://github.com/Flutterando/desafios). Publish the code on GitHub with a README and screenshots.
8. **Publish an app to the stores.** Follow the [Google Play launch checklist](https://developer.android.com/distribute/best-practices/launch/launch-checklist) and the [App Store review guidelines](https://developer.apple.com/app-store/review/guidelines/). A published app is worth more than ten certificates in an interview.

Your first app in 2 minutes (Flutter):

```bash
flutter doctor                      # checks SDK, Android Studio/Xcode and devices
flutter create hello_mobile && cd hello_mobile
flutter run                         # runs on the emulator or the connected phone
```

And "Hello, world" in Jetpack Compose (native Android):

```kotlin
@Composable
fun Greeting(name: String) {
    Text(text = "Hello, $name!")
}

@Preview(showBackground = true)
@Composable
fun GreetingPreview() {
    Greeting("Guia Dev Brasil")   // shows up in the Android Studio preview, no emulator needed
}
```

## 🎓 Free courses
### In Portuguese
- [Noções básicas do Android com o Compose (Google, PT-BR)](https://developer.android.com/courses/android-basics-compose/course?hl=pt-br) — Google's official free course, translated to Portuguese, teaching Kotlin and Jetpack Compose from scratch with projects per unit. 🆕
- [Jetpack Compose para desenvolvedores Android (Google, PT-BR)](https://developer.android.com/courses/jetpack-compose/course?hl=pt-br) — Official course for people who already build Android apps and want to move from XML to Compose. 🆕
- [Codelabs do Android (PT-BR)](https://developer.android.com/get-started/codelabs?hl=pt-br) — Free guided tutorials by Google, many translated, covering Compose, architecture, Room, testing and more.
- [Iniciante em Android com Jetpack Compose (Alex Felipe)](https://www.youtube.com/playlist?list=PLYaQbIm_3oZ9BwznyXn7n_Zl1KBq3I9oO) — Free playlist by a former Alura instructor, building an Android app with Compose step by step.
- [Curso de Jetpack Compose com Kotlin: Iniciantes (Android — Simples e Direto)](https://www.youtube.com/watch?v=g7TDiEDTReM) — Long, straight-to-the-point lesson for a first contact with Compose, no prior Android experience assumed.
- [Curso de Swift — Desenvolvimento iOS Apple (Portal Hugo Cursos)](https://www.youtube.com/playlist?list=PLxNM4ef1BpxjjMKpcYSqXI4eY4tZG2csm) — Portuguese playlist with dozens of short lessons on the Swift language and Xcode.
- [Aprenda Swift — lista de conteúdos (Codando Apple)](https://github.com/CodandoApple/aprenda-swift) — Brazilian repository with free materials organized to learn Swift, SwiftUI and iOS.
- [Curso grátis Swift e SwiftUI — Stanford CS193p (curadoria de Filipe Deschamps)](https://www.youtube.com/playlist?list=PLMdYygf53DP46rneFgJ7Ab6fJPcMvr8gC) — Playlist with the Stanford iOS course lectures (in English) plus a Portuguese intro video on how to follow it. 🇺🇸
- [Curso COMPLETO de Flutter (Flutterando)](https://www.youtube.com/playlist?list=PLlBnICoI-g-d-J57QIz6Tx5xtUDGQdBFB) — Course from Brazil's largest Flutter community, from basic Dart to publishing.
- [Curso de Flutter COMPLETO — Cursa (Flutterando, com certificado)](https://cursa.com.br/curso-de-flutter-completo/513) — Flutterando's content organized on a free platform that issues a certificate; updated in 2024. 🆕
- [Curso Flutter Básico [NV1] (Deivid Willyan)](https://www.youtube.com/playlist?list=PLRpTFz5_57cvo0CHf-AnojOvpznz8YO7S) — First level of a free, very didactic series on widgets, layouts and navigation.
- [Curso Gratuito de Flutter 2024 (AbnerCasalloTECH)](https://www.youtube.com/playlist?list=PLHgdJafeca0nFak4Jj1aKXglmswsPbE1b) — Recent Portuguese playlist covering Flutter 3 and modern Dart. 🆕
- [Curso de Flutter e Dart (daves tecnologia)](https://www.youtube.com/playlist?list=PL5EmR7zuTn_aX0pG4oWTyKKQT25Hkq2XG) — Free course, one concept per video, starting with the Dart language.
- [Introdução ao Flutter (DIO)](https://www.dio.me/courses/introducao-ao-flutter) — Free DIO course with certificate for a first contact with Flutter.
- [Primeiros Passos com React Native & Expo (DIO)](https://www.dio.me/courses/primeiros-passos-com-react-native-expo) — Free course with certificate: environment, Expo and a first app.
- [Curso completo de React Native + Expo — do zero (DevClub)](https://www.youtube.com/watch?v=a8YvzTXft9c) — Single, complete lesson published in 2025, building an app for iPhone and Android with Expo. 🆕
- [Curso de React Native + Expo (Jovem Programador)](https://www.youtube.com/playlist?list=PLqfQXYWB7zobw0ruLOoeAKCCc7_jQo-JN) — Portuguese playlist with the modern Expo workflow, lesson by lesson.
- [Curso de React Native — app iOS e Android (Portal Hugo Cursos)](https://www.youtube.com/playlist?list=PLxNM4ef1Bpxhe_PxwprF0R2fp0UurDZuw) — Series of short Portuguese lessons covering components, styles and navigation.
- [Kotlin Multiplatform — curso do zero ao avançado (CodandoTV)](https://www.youtube.com/watch?v=2_dYJr1s5Ak) — Portuguese course published in 2025 on KMP and Compose Multiplatform: one codebase for Android and iOS. 🆕
- [Apple Developer Academy — Mackenzie (São Paulo)](https://developeracademy.mackenzie.br/) — Free two-year Apple program with the university; selection process for the 2027/2028 cohort. 🆕
- [Apple Developer Academy — IFCE (Fortaleza)](https://developeracademy.ifce.edu.br/) — Apple Developer Academy site in Ceará, free, focused on iOS development and app design. 🆕
- [Apple Developer Academies (página oficial da Apple)](https://developer.apple.com/academies/) — Official list of all academies worldwide, including the Brazilian sites. 🇺🇸
- [Learn X in Y minutes — Kotlin (PT-BR)](https://learnxinyminutes.com/pt-br/kotlin/) — The whole Kotlin syntax in one commented file, in Portuguese.
- [Learn X in Y minutes — Swift (PT-BR)](https://learnxinyminutes.com/pt-br/swift/) — The whole Swift syntax in one commented file, in Portuguese.
- [Learn X in Y minutes — Dart (PT-BR)](https://learnxinyminutes.com/pt-br/dart/) — The whole Dart syntax in one commented file, in Portuguese.

### In English
- [Develop in Swift Tutorials (Apple)](https://developer.apple.com/tutorials/develop-in-swift/) — Apple's official, current tutorials to learn Swift and SwiftUI by building real apps in Xcode. 🆕 🇺🇸
- [Introducing SwiftUI (Apple)](https://developer.apple.com/tutorials/swiftui/) — Apple's classic official tutorial: a complete landmarks app with SwiftUI. 🇺🇸
- [Develop apps for Apple platforms (Apple)](https://developer.apple.com/tutorials/app-dev-training/) — Official course with the Scrumdinger app: SwiftUI, data, audio and persistence. 🇺🇸
- [Learning SwiftUI (Apple)](https://developer.apple.com/tutorials/swiftui-concepts) — SwiftUI concepts explained with short examples: layout, state, navigation and animation. 🇺🇸
- [100 Days of SwiftUI (Hacking with Swift)](https://www.hackingwithswift.com/100/swiftui) — Paul Hudson's free 100-day course with projects and daily tests; the most recommended for SwiftUI. 🇺🇸
- [CS193p — Developing Apps for iOS (Stanford)](https://cs193p.stanford.edu/) — Stanford's iOS course with free video lectures on Swift and SwiftUI. 🇺🇸
- [Tour of Kotlin (oficial)](https://kotlinlang.org/docs/kotlin-tour-welcome.html) — Official interactive tour of the Kotlin language, with exercises running in the browser. 🆕 🇺🇸
- [Kotlin Koans](https://kotlinlang.org/docs/koans.html) — Official exercises to learn Kotlin syntax and idioms by fixing failing tests. 🇺🇸
- [Get started with Kotlin Multiplatform (oficial)](https://kotlinlang.org/docs/multiplatform/get-started.html) — JetBrains' official tutorial: first Android + iOS app sharing Kotlin code. 🆕 🇺🇸
- [Create your Compose Multiplatform app (oficial)](https://kotlinlang.org/docs/multiplatform/compose-multiplatform-create-first-app.html) — Official tutorial for shared UI with Compose Multiplatform on Android, iOS and desktop. 🆕 🇺🇸
- [Flutter learning pathway (oficial)](https://docs.flutter.dev/learn/pathway) — Flutter's official path: fundamentals, first-app codelab and next steps. 🆕 🇺🇸
- [Google Codelabs — Flutter](https://codelabs.developers.google.com/?product=flutter) — Google's official codelabs filtered by Flutter: layouts, animations, Firebase, testing. 🇺🇸
- [Introduction to Flutter Development with Dart (The App Brewery)](https://www.appbrewery.com/p/intro-to-flutter) — Angela Yu's free course, made with Google, for Flutter beginners. 🇺🇸
- [Expo Tutorial — Using React Native and Expo (oficial)](https://docs.expo.dev/tutorial/introduction/) — Expo's official tutorial: a complete app with camera, gestures and publishing. 🆕 🇺🇸
- [React Native Express](https://www.reactnative.express/) — Free interactive guide walking through React Native with runnable examples. 🇺🇸
- [Flutter Course for Beginners — 37 horas (freeCodeCamp)](https://www.youtube.com/watch?v=VPvVD8t02U8) — Complete video course, from Dart to a published app. 🇺🇸
- [Learn Kotlin Programming — Full Course (freeCodeCamp)](https://www.youtube.com/watch?v=EExSSotojVI) — Complete Kotlin course for beginners. 🇺🇸
- [Swift Programming Tutorial — Full Course (Sean Allen)](https://www.youtube.com/watch?v=CwA1VWP0Ldw) — Swift course for absolute beginners, straight to the point. 🇺🇸
- [Master React Native 2024 — Expo Router, TypeScript, Zustand (HuXn WebDev)](https://www.youtube.com/watch?v=a_SthPXtV6c) — Long, up-to-date course with the modern React Native stack. 🆕 🇺🇸
- [React Native Full Course 2026 — Build a Mobile App Using Expo (PedroTech)](https://www.youtube.com/watch?v=RdJhqaOIWn0) — Recent course building a complete app with Expo. 🆕 🇺🇸

## 💰 Paid courses
- [Formação Desenvolva seu primeiro app Android com Kotlin (Alura)](https://www.alura.com.br/formacao-android-kotlin) — Alura track from Android Studio to a first Compose app; certificate recognized in the Brazilian market. 💰
- [Formação Evolua apps Android com Jetpack Compose (Alura)](https://www.alura.com.br/formacao-jetpack-compose-criando-telas-gerenciando-estados) — Follow-up: screens, state, ViewModel and StateFlow with Compose. 💰
- [Formação Domine a linguagem Swift (Alura)](https://www.alura.com.br/formacao-domine-linguagem-swift) — Alura track to learn Swift and take the first steps in iOS. 💰
- [Carreira Desenvolvimento Mobile com Flutter (Alura)](https://www.alura.com.br/carreiras/desenvolvimento-mobile-com-flutter) — Alura's complete Flutter career track, from Dart to publishing. 💰
- [Formação React Native (Rocketseat)](https://www.rocketseat.com.br/formacao/react-native) — Rocketseat's track with hands-on React Native and Expo projects. 💰
- [Academia do Flutter (Rodrigo Rahman)](https://academiadoflutter.com.br/) — Well-known complete Dart and Flutter course in Portuguese, focused on real projects. 💰
- [Meta Android Developer Professional Certificate (Coursera)](https://www.coursera.org/professional-certificates/meta-android-developer) — Meta's Kotlin and Android program with a professional certificate; lectures can be audited for free. 💰 🇺🇸
- [Meta iOS Developer Professional Certificate (Coursera)](https://www.coursera.org/professional-certificates/meta-ios-developer) — Meta's Swift and iOS program with a professional certificate. 💰 🇺🇸
- [Meta React Native Specialization (Coursera)](https://www.coursera.org/specializations/meta-react-native) — Meta's React Native specialization, from foundations to a capstone project. 💰 🇺🇸
- [Hacking with Swift+](https://www.hackingwithswift.com/plus) — Paul Hudson's subscription with advanced Swift and SwiftUI tutorials. 💰 🇺🇸
- [PL Coding (Philipp Lackner)](https://www.pl-coding.com/) — Industry-level Android and KMP courses from the creator of one of the largest Android channels. 🆕 💰 🇺🇸

## 📖 Documentation
### Android (Kotlin and Jetpack Compose)
- [Android Developers — documentação](https://developer.android.com/docs) — Android's official documentation portal: guides, API reference and samples. 🇺🇸
- [Primeiros passos com o Jetpack Compose (PT-BR)](https://developer.android.com/develop/ui/compose/documentation?hl=pt-br) — Official Compose documentation in Portuguese: layout, state, navigation, animation and testing.
- [Kotlin e Android (PT-BR)](https://developer.android.com/kotlin?hl=pt-br) — Why Kotlin is Android's official language, with guides and samples in Portuguese.
- [Guide to app architecture](https://developer.android.com/topic/architecture) — Official architecture guide: UI, domain and data layers, unidirectional data flow and ViewModel. 🇺🇸
- [State and Jetpack Compose](https://developer.android.com/develop/ui/compose/state) — How state works in Compose: hoisting, remember, ViewModel and recomposition. 🇺🇸
- [Room — banco de dados local](https://developer.android.com/training/data-storage/room) — Official persistence library on top of SQLite, with Kotlin coroutines and Flow. 🇺🇸
- [Kotlin coroutines on Android](https://developer.android.com/kotlin/coroutines) — Official guide to concurrency on Android with coroutines and Flow. 🇺🇸
- [Android Jetpack](https://developer.android.com/jetpack) — Official library suite (Compose, Navigation, Room, WorkManager, Hilt) that every team uses. 🇺🇸
- [Kotlin Docs (oficial)](https://kotlinlang.org/docs/home.html) — Official Kotlin language documentation, with reference and per-platform guides. 🇺🇸
- [Material Design 3](https://m3.material.io/) — Google's official design system: components, dynamic color, typography and guidelines. 🇺🇸
- [Build accessible apps](https://developer.android.com/guide/topics/ui/accessibility) — Official Android accessibility guide: TalkBack, labels, contrast and touch targets. 🇺🇸
- [Security checklist (Android)](https://developer.android.com/privacy-and-security/security-tips) — Official security practices checklist: permissions, storage, networking and cryptography. 🇺🇸

### iOS (Swift and SwiftUI)
- [Apple Developer Documentation](https://developer.apple.com/documentation/) — Official documentation portal for all Apple frameworks. 🇺🇸
- [SwiftUI (documentação oficial)](https://developer.apple.com/documentation/swiftui/) — Official SwiftUI reference: views, layout, navigation, data and animation. 🇺🇸
- [The Swift Programming Language (livro oficial)](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/) — Official free Swift language book, always updated to the current version. 🇺🇸
- [Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/) — Apple's official design guidelines for iOS, iPadOS, watchOS, macOS and visionOS. 🇺🇸
- [SwiftData](https://developer.apple.com/documentation/swiftdata) — Apple's modern persistence framework, integrated with SwiftUI and Swift concurrency. 🇺🇸
- [Apple Design Resources](https://developer.apple.com/design/resources/) — Official UI kits for Figma and Sketch, SF fonts and icon templates. 🇺🇸
- [Accessibility (Apple)](https://developer.apple.com/documentation/accessibility) — Official accessibility documentation: VoiceOver, Dynamic Type and Xcode audits. 🇺🇸
- [Xcode (documentação)](https://developer.apple.com/documentation/xcode) — Official Xcode documentation: projects, simulator, testing, previews and distribution. 🇺🇸

### Cross-platform (Flutter, React Native, Kotlin Multiplatform)
- [Flutter Brasil — documentação em português](https://flutterbrasil.dev/) — Community-run, officially recognized Portuguese translation of the Flutter site, with docs and guides. 🆕
- [Flutter documentation (oficial)](https://docs.flutter.dev/) — Official Flutter documentation: install, widgets, state, testing, deployment and performance. 🇺🇸
- [Dart documentation (oficial)](https://dart.dev/docs) — Official Dart language documentation, with the language guide and core libraries. 🇺🇸
- [Flutter — Widget catalog](https://docs.flutter.dev/ui/widgets) — Official widget catalog by category (Material, Cupertino, layout, input). 🇺🇸
- [Flutter — State management](https://docs.flutter.dev/data-and-backend/state-mgmt/intro) — Official introduction to state management and the options (Provider, Riverpod, Bloc). 🇺🇸
- [Flutter for Android developers](https://docs.flutter.dev/flutter-for/android-devs) — Official transition guide for people who already know native Android. 🇺🇸
- [Flutter for React Native developers](https://docs.flutter.dev/flutter-for/react-native-devs) — Official transition guide for people coming from React Native. 🇺🇸
- [React Native — documentação (oficial)](https://reactnative.dev/docs/getting-started) — Official React Native documentation: components, native APIs, the New Architecture and publishing. 🇺🇸
- [Expo Documentation (oficial)](https://docs.expo.dev/) — Expo documentation, the framework recommended by the React Native team: SDK, EAS and Expo Router. 🆕 🇺🇸
- [Expo Router](https://docs.expo.dev/router/introduction/) — File-based navigation for React Native, with deep links and web. 🆕 🇺🇸
- [Kotlin Multiplatform (oficial)](https://kotlinlang.org/multiplatform/) — Official KMP page: share logic (and UI, with Compose Multiplatform) across Android, iOS, web and desktop. 🆕 🇺🇸
- [Compose Multiplatform (oficial)](https://kotlinlang.org/compose-multiplatform/) — JetBrains' declarative UI for Android, iOS (stable since 2025), desktop and web. 🆕 🇺🇸
- [Kotlin Multiplatform Wizard](https://kmp.jetbrains.com/) — Official KMP project generator: pick the platforms and download a ready skeleton. 🆕 🇺🇸
- [O que é .NET MAUI? (Microsoft Learn, PT-BR)](https://learn.microsoft.com/pt-br/dotnet/maui/what-is-maui?view=net-maui-10.0) — Portuguese documentation for Microsoft's cross-platform C# framework.
- [Capacitor](https://capacitorjs.com/) — Native runtime to turn web apps into iOS and Android apps with native API access. 🇺🇸
- [Firebase — documentação (PT-BR)](https://firebase.google.com/docs?hl=pt-br) — Portuguese docs for the most used backend in mobile apps: auth, Firestore, push, Crashlytics.

### Store publishing and security
- [Publish your app (Android Studio)](https://developer.android.com/studio/publish) — Official guide: signing, App Bundle, versioning and preparing for Google Play. 🇺🇸
- [Launch checklist (Google Play)](https://developer.android.com/distribute/best-practices/launch/launch-checklist) — Official launch checklist: policies, testing, listing, pricing and distribution. 🇺🇸
- [Ajuda do Play Console (PT-BR)](https://support.google.com/googleplay/android-developer/?hl=pt-BR) — Official help center in Portuguese: developer account, policies, releases and monetization.
- [Preparar e lançar uma versão (Play Console, PT-BR)](https://support.google.com/googleplay/android-developer/answer/9859348?hl=pt-BR) — Official Portuguese step-by-step to create and roll out a release on Google Play.
- [Google Play Academy](https://playacademy.withgoogle.com/) — Free Google courses on Play Console, policies, store listing and monetization, with a certificate. 🇺🇸
- [App Review Guidelines (App Store)](https://developer.apple.com/app-store/review/guidelines/) — Official App Store review rules; read before submitting to avoid rejections. 🇺🇸
- [Submitting to the App Store](https://developer.apple.com/app-store/submitting/) — Apple's official page with the submission process and what to prepare. 🇺🇸
- [App Store Connect — Help](https://developer.apple.com/help/app-store-connect/) — Official App Store Connect manual: builds, TestFlight, pricing, metadata and release. 🇺🇸
- [Apple Developer Program](https://developer.apple.com/programs/) — How to enroll in the (annual, paid) program required to publish on the App Store. 🇺🇸
- [TestFlight](https://developer.apple.com/testflight/) — Apple's official beta distribution for internal and external testers. 🇺🇸
- [Flutter — Build and release an Android app](https://docs.flutter.dev/deployment/android) — Flutter's official guide to build a signed App Bundle and publish on Google Play. 🇺🇸
- [Flutter — Build and release an iOS app](https://docs.flutter.dev/deployment/ios) — Flutter's official guide to archive in Xcode and publish on the App Store. 🇺🇸
- [Expo — Submit to app stores](https://docs.expo.dev/deploy/submit-to-app-stores/) — How to send builds to the stores with EAS Submit. 🆕 🇺🇸
- [React Native — Publishing to Google Play Store](https://reactnative.dev/docs/signed-apk-android) — Official guide to signing and publishing React Native apps on Android. 🇺🇸
- [React Native — Publishing to Apple App Store](https://reactnative.dev/docs/publishing-to-app-store) — Official guide to publishing React Native apps on the App Store. 🇺🇸
- [OWASP Mobile Application Security (MAS)](https://mas.owasp.org/) — Security standard and testing guide for mobile apps, the reference in audits. 🇺🇸

## 📚 Books
- [Kotlin com Android (Casa do Código)](https://www.casadocodigo.com.br/products/livro-kotlin-android) — Portuguese book on building Android apps with Kotlin, from Brazilian publisher Casa do Código. 💰
- [Flutter (Casa do Código)](https://www.casadocodigo.com.br/products/livro-flutter) — Portuguese book on Flutter and Dart for Android and iOS apps. 💰
- [React Native (Casa do Código)](https://www.casadocodigo.com.br/products/livro-react-native) — Portuguese book on React Native, from setup to publishing. 💰
- [Kotlin em ação (Novatec)](https://novatec.com.br/livros/kotlin-em-acao/) — Portuguese translation of the classic written by members of JetBrains' Kotlin team. 💰
- [Flutter na prática (Novatec)](https://novatec.com.br/livros/flutter-na-pratica/) — Portuguese translation of Flutter in Action, with complete projects. 💰
- [The Swift Programming Language (gratuito)](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/) — The official Swift book, online and free, from the language tour to the grammar reference. 🇺🇸
- [Hacking with iOS (gratuito online)](https://www.hackingwithswift.com/read) — Paul Hudson's book of iOS projects, free to read on the site. 🇺🇸
- [SwiftUI by Example (gratuito)](https://www.hackingwithswift.com/quick-start/swiftui) — Free reference book with hundreds of short SwiftUI recipes. 🇺🇸
- [Kotlin in Action, Second Edition (Manning)](https://www.manning.com/books/kotlin-in-action-second-edition) — Second edition (2024) of the definitive Kotlin book, now with coroutines and Flow. 🆕 💰 🇺🇸
- [Effective Kotlin (Kt. Academy)](https://kt.academy/book/effectivekotlin) — Kotlin best practices, item by item, by Marcin Moskała. 💰 🇺🇸
- [Kotlin Coroutines: Deep Dive (Kt. Academy)](https://kt.academy/book/coroutines) — The most complete book on coroutines and Flow, essential in modern Android. 💰 🇺🇸
- [Flutter in Action (Manning)](https://www.manning.com/books/flutter-in-action) — Complete introduction to Flutter and Dart with an app built throughout the book. 💰 🇺🇸
- [Flutter Apprentice (Kodeco)](https://www.kodeco.com/books/flutter-apprentice) — Kodeco's book for Flutter beginners, with guided projects. 💰 🇺🇸
- [React Native in Action (Manning)](https://www.manning.com/books/react-native-in-action) — Nader Dabit's book on React Native, from basics to native modules. 💰 🇺🇸
- [Big Mountain Studio — livros visuais de SwiftUI](https://www.bigmountainstudio.com/) — Visual SwiftUI reference books (views, animations, data), widely used in the industry. 💰 🇺🇸

## 🎥 YouTube channels
### In Portuguese
- [Flutterando](https://www.youtube.com/@Flutterando) — Channel of Brazil's largest Flutter community: courses, live streams and architecture.
- [Rodrigo Rahman](https://www.youtube.com/@RodrigoRahman) — Flutter and Dart in depth, by the creator of Academia do Flutter.
- [Deivid Willyan | Flutter](https://www.youtube.com/@FlutterCursos) — Free Flutter courses by level and career tips.
- [Toshi Ossada](https://www.youtube.com/@Toshiossada) — Flutter, Dart and app architecture, with live projects.
- [Alex Felipe](https://www.youtube.com/@AlexFelipeDev) — Android with Kotlin and Jetpack Compose explained calmly for beginners.
- [Android — Simples e Direto](https://www.youtube.com/@androidsimplesedireto) — Free Android and Compose courses in Portuguese.
- [Douglas Motta](https://www.youtube.com/@DouglasMotta) — Modern Android, architecture, testing and career, by a Brazilian Android engineer.
- [Android Dev BR](https://www.youtube.com/@AndroidDevBr) — Talks and live streams from the Brazilian Android community.
- [Lucas Montano](https://www.youtube.com/@LucasMontano) — Kotlin, Android and an international big-tech career, with direct opinions.
- [CodandoTV](https://www.youtube.com/@CodandoTV) — Kotlin Multiplatform and Compose Multiplatform in Portuguese, with complete courses published in 2025. 🆕
- [CocoaHeads Brasil](https://www.youtube.com/@cocoaheadsbr) — Talks from the Brazilian iOS/Swift community meetups.
- [Portal Hugo Cursos](https://www.youtube.com/@tutoriais01) — Free, extensive courses on Swift, React Native and other technologies.
- [Rocketseat](https://www.youtube.com/@rocketseat) — Free events and lessons on React Native and Expo, among other stacks.
- [Matheus Battisti — Hora de Codar](https://www.youtube.com/@MatheusBattisti) — Free React Native and JavaScript courses for beginners.
- [DevClub | Programação](https://www.youtube.com/@canaldevclub) — Complete React Native + Expo lessons, including the 2025 from-scratch course. 🆕

### In English
- [Android Developers (oficial)](https://www.youtube.com/@AndroidDevelopers) — Google's official channel: Now in Android, Compose, what's new in each release. 🇺🇸
- [Kotlin by JetBrains (oficial)](https://www.youtube.com/@Kotlin) — Official Kotlin channel: KotlinConf, KMP and tutorials. 🇺🇸
- [Flutter (oficial)](https://www.youtube.com/@flutterdev) — Official Flutter channel: Widget of the Week, news and codelabs. 🇺🇸
- [Apple Developer (oficial)](https://www.youtube.com/@AppleDeveloper) — Apple's official channel with WWDC sessions and tutorials. 🇺🇸
- [Expo (oficial)](https://www.youtube.com/@ExpoDevelopers) — Expo's official channel with tutorials and releases. 🇺🇸
- [Philipp Lackner](https://www.youtube.com/@PhilippLackner) — One of the largest Android channels: Compose, architecture, KMP and best practices. 🇺🇸
- [Stevdza-San](https://www.youtube.com/@StevdzaSan) — Android tutorials with Kotlin, Compose and KMP. 🇺🇸
- [Paul Hudson (Hacking with Swift)](https://www.youtube.com/@twostraws) — Swift and SwiftUI by the author of 100 Days of SwiftUI. 🇺🇸
- [Sean Allen](https://www.youtube.com/@seanallen) — Swift, SwiftUI and iOS career in objective videos. 🇺🇸
- [Swiftful Thinking](https://www.youtube.com/@SwiftfulThinking) — SwiftUI playlists from beginner to advanced, including architecture. 🇺🇸
- [Reso Coder](https://www.youtube.com/@ResoCoder) — Flutter with architecture, testing and Bloc. 🇺🇸
- [Andrea Bizzotto (Code with Andrea)](https://www.youtube.com/@codewithandrea) — Professional Flutter: Riverpod, Firebase and production apps. 🇺🇸
- [notJust.dev](https://www.youtube.com/@notjustdev) — React Native and Expo with clones of real apps, live. 🇺🇸
- [William Candillon](https://www.youtube.com/@wcandillon) — Advanced animations and gestures in React Native with Reanimated and Skia. 🇺🇸
- [Simon Grimm](https://www.youtube.com/@galaxies_dev) — React Native, Expo and Ionic with complete projects. 🇺🇸

## 🎙️ Podcasts
- [Hipsters Ponto Tech](https://www.hipsters.tech/) — Alura's Brazilian tech podcast, with episodes on Flutter, Android, iOS and career.
- [Universo Flutter](https://creators.spotify.com/pod/profile/universoflutter/) — Portuguese podcast dedicated to Flutter and the mobile market.
- [Android Developers Backstage](https://adbackstage.libsyn.com/) — Official podcast of Google's Android team. 🇺🇸
- [Talking Kotlin](https://talkingkotlin.com/) — JetBrains' podcast with the Kotlin team and community. 🇺🇸
- [Fragmented](https://fragmentedpodcast.com/) — Veteran podcast on Android development and software engineering. 🇺🇸
- [Swift by Sundell — Podcast](https://www.swiftbysundell.com/podcast/) — Conversations with iOS developers about Swift and architecture. 🇺🇸
- [It's All Widgets! — Flutter Podcast](https://itsallwidgets.com/podcast) — Interviews with Flutter developers about real apps. 🇺🇸
- [React Native Radio](https://infinite.red/react-native-radio) — Infinite Red's podcast on the React Native ecosystem. 🇺🇸
- [Now in Android](https://developer.android.com/series/now-in-android) — Official series (video, podcast and newsletter) with Android news every two weeks. 🇺🇸

## 📰 Sites, blogs and newsletters
- [Kotlin Brasil](https://kotlin.dev.br/) — Brazilian Kotlin community site with articles, events and community links. 🆕
- [Alura — artigos de Mobile](https://www.alura.com.br/artigos/mobile) — Portuguese articles on Android, iOS, Flutter and React Native.
- [TabNews](https://www.tabnews.com.br/) — Brazilian technical-content community; search for Flutter, Android or iOS.
- [Android Developers Blog](https://android-developers.googleblog.com/) — Official Android blog with releases, Play policies and tooling news. 🇺🇸
- [Android Weekly](https://androidweekly.net/) — Free weekly newsletter with the best Android and Kotlin articles. 🇺🇸
- [Kotlin Blog (JetBrains)](https://blog.jetbrains.com/kotlin/) — Official Kotlin blog: releases, KMP and Compose Multiplatform. 🇺🇸
- [iOS Dev Weekly](https://iosdevweekly.com/) — The most traditional weekly iOS newsletter, curated by Dave Verwer. 🇺🇸
- [Swift by Sundell](https://www.swiftbysundell.com/) — Swift and SwiftUI articles by John Sundell. 🇺🇸
- [Hacking with Swift](https://www.hackingwithswift.com/) — The largest site of free Swift, SwiftUI and iOS tutorials. 🇺🇸
- [SwiftLee](https://swiftlee.com/) — Weekly articles by Antoine van der Lee on Swift, Xcode and SwiftUI. 🇺🇸
- [Apple Developer — Videos (WWDC)](https://developer.apple.com/videos/) — All WWDC sessions, the main source of iOS and Swift news. 🇺🇸
- [Flutter — tag na DEV Community](https://dev.to/t/flutter) — Community articles on Flutter, many in Portuguese.
- [React Native — Blog oficial](https://reactnative.dev/blog) — Release and New Architecture announcements. 🇺🇸
- [Expo Blog](https://expo.dev/blog) — SDK, EAS and Expo Router news. 🇺🇸
- [This Week in React](https://thisweekinreact.com/) — Weekly React newsletter with a dedicated React Native section. 🇺🇸
- [React Native Newsletter](https://reactnativenewsletter.com/) — Free newsletter with the best of the React Native ecosystem. 🇺🇸
- [State of Mobile 2025 (Sensor Tower)](https://sensortower.com/state-of-mobile-2025) — Annual mobile market report: downloads, revenue and trends. 🆕 🇺🇸

## 🛠️ Tools
### IDEs, emulators and environment
- [Android Studio (PT-BR)](https://developer.android.com/studio?hl=pt-br) — The official Android IDE, with emulator, profiler, Compose Preview and built-in Gemini.
- [Xcode](https://developer.apple.com/xcode/) — Apple's official IDE for iOS, with simulator, SwiftUI previews and a coding assistant. 🇺🇸
- [Visual Studio Code](https://code.visualstudio.com/) — The most used editor for Flutter and React Native, with official extensions. 🇺🇸
- [Install Flutter (oficial)](https://docs.flutter.dev/install) — Official guide to install the Flutter SDK on macOS, Windows and Linux. 🇺🇸
- [Expo Go](https://expo.dev/go) — App to run your React Native project on your phone without compiling native code. 🇺🇸
- [Kotlin Playground](https://play.kotlinlang.org/) — Run Kotlin in the browser without installing anything. 🇺🇸
- [Swift Playground](https://developer.apple.com/swift-playground/) — Apple's free iPad and Mac app that teaches Swift and lets you build complete apps. 🇺🇸
- [DartPad](https://dartpad.dev/) — Official online Dart and Flutter editor. 🇺🇸
- [Expo Snack](https://snack.expo.dev/) — React Native in the browser, with phone preview through Expo Go. 🇺🇸
- [Android Debug Bridge (adb)](https://developer.android.com/tools/adb) — Command-line tool to install apps, read logs and control devices. 🇺🇸
- [scrcpy](https://github.com/Genymobile/scrcpy) — Mirror and control a real Android device from your computer, free and root-less. 🇺🇸
- [FVM — Flutter Version Management](https://fvm.app/) — Manage several Flutter versions per project. 🇺🇸
- [pub.dev](https://pub.dev/) — Official Dart and Flutter package repository, with quality scores. 🇺🇸

### Libraries and backend
- [Hilt (injeção de dependência)](https://developer.android.com/training/dependency-injection/hilt-android) — Official DI solution for Android, built on Dagger. 🇺🇸
- [Koin](https://insert-koin.io/) — Pragmatic dependency injection in Kotlin, also for KMP. 🇺🇸
- [Ktor](https://ktor.io/) — JetBrains' Kotlin HTTP client (and server), the standard in KMP projects. 🇺🇸
- [SQLDelight](https://sqldelight.github.io/sqldelight/) — Generates typed Kotlin code from SQL; works on Android, iOS and KMP. 🇺🇸
- [SKIE](https://skie.touchlab.co/) — Improves Kotlin → Swift interop in KMP projects (enums, Flow, suspend). 🆕 🇺🇸
- [Riverpod](https://riverpod.dev/) — Reactive state management for Flutter, the evolution of Provider. 🇺🇸
- [Bloc](https://bloclibrary.dev/) — BLoC pattern for Flutter: predictable, testable state. 🇺🇸
- [Drift](https://drift.simonbinder.eu/) — Reactive, typed persistence over SQLite for Flutter. 🇺🇸
- [React Navigation](https://reactnavigation.org/) — React Native's standard navigation library. 🇺🇸
- [React Native Reanimated](https://docs.swmansion.com/react-native-reanimated/) — Animations and gestures running on the UI thread. 🇺🇸
- [Firebase](https://firebase.google.com/) — Google's managed backend: auth, database, storage, push, analytics and crash reports. 🇺🇸
- [Supabase](https://supabase.com/) — Open-source Firebase alternative with Postgres, auth and realtime; SDKs for Flutter, Swift, Kotlin and RN. 🇺🇸
- [RevenueCat](https://www.revenuecat.com/) — In-app subscriptions and purchases for iOS, Android, Flutter and RN, without handling the stores directly. 🇺🇸

### Testing, debugging and monitoring
- [Test your Compose layout](https://developer.android.com/develop/ui/compose/testing) — Official guide to UI testing in Jetpack Compose. 🇺🇸
- [XCTest](https://developer.apple.com/documentation/xctest) — Apple's official unit and UI testing framework. 🇺🇸
- [Testing Flutter apps](https://docs.flutter.dev/testing/overview) — Official guide to unit, widget and integration tests in Flutter. 🇺🇸
- [Maestro](https://docs.maestro.dev/) — YAML-based E2E UI tests for Android, iOS, Flutter and React Native; the easiest to adopt. 🆕 🇺🇸
- [Patrol](https://patrol.leancode.co/) — E2E tests for Flutter with access to native permissions, notifications and WebViews. 🆕 🇺🇸
- [Detox](https://wix.github.io/Detox/) — Gray-box E2E testing for React Native. 🇺🇸
- [detekt](https://detekt.dev/) — Static analysis for Kotlin code. 🇺🇸
- [SwiftLint](https://github.com/realm/SwiftLint) — Style and conventions linter for Swift. 🇺🇸
- [Proxyman](https://proxyman.com/) — HTTP proxy to inspect app traffic on iOS and Android. 🇺🇸
- [Firebase Crashlytics](https://firebase.google.com/products/crashlytics) — Real-time crash reporting, free, for Android, iOS, Flutter and RN. 🇺🇸
- [Sentry for Mobile](https://sentry.io/solutions/mobile-developers/) — Error and performance monitoring with SDKs for every mobile stack. 🇺🇸

### Publishing, CI/CD and design
- [fastlane](https://fastlane.tools/) — Automates screenshots, signing, builds and store uploads. 🇺🇸
- [Codemagic](https://codemagic.io/start/) — CI/CD built for mobile (Flutter, RN, native), with a free plan. 🇺🇸
- [GitHub Actions (documentação em PT-BR)](https://docs.github.com/pt/actions) — Free CI for public projects; macOS runners for iOS builds.
- [Xcode Cloud](https://developer.apple.com/xcode-cloud/) — Apple's CI/CD integrated with Xcode and TestFlight, with free hours. 🇺🇸
- [Expo Application Services (EAS)](https://expo.dev/services) — Cloud build, submit and OTA updates for React Native apps. 🇺🇸
- [Shorebird](https://shorebird.dev/) — Code push (updates without going through the store) for Flutter. 🆕 🇺🇸
- [Figma](https://www.figma.com/) — Standard interface design tool; use it with Apple's and Material's official kits. 🇺🇸
- [SF Symbols](https://developer.apple.com/sf-symbols/) — Apple's official library of thousands of icons, integrated with SwiftUI. 🇺🇸
- [FlutterFlow](https://flutterflow.io/) — Visual (low-code) builder that exports Flutter code. 💰 🇺🇸

## 🧪 Hands-on projects and challenges
- [Now in Android (app oficial)](https://github.com/android/nowinandroid) — Google's complete app demonstrating the recommended architecture with Compose, Hilt and Room. 🇺🇸
- [Jetpack Compose samples (oficial)](https://github.com/android/compose-samples) — Official Compose samples (Jetnews, Jetchat, Jetsnack) to study UI. 🇺🇸
- [Pokedex Compose (skydoves)](https://github.com/skydoves/pokedex-compose) — Modern Android reference project: Compose, Hilt, Retrofit and Room. 🆕 🇺🇸
- [KMP production sample (Kotlin)](https://github.com/kotlin/kmp-production-sample) — Real RSS app in Kotlin Multiplatform maintained by JetBrains. 🇺🇸
- [Kotlin Multiplatform samples (oficial)](https://kotlinlang.org/docs/multiplatform/multiplatform-samples.html) — Official list of KMP samples by use case. 🆕 🇺🇸
- [Food Truck (Apple, WWDC22)](https://github.com/apple/sample-food-truck) — Apple's SwiftUI sample app for iPhone, iPad and Mac. 🇺🇸
- [Flutter samples (oficial)](https://github.com/flutter/samples) — Official collection of Flutter samples and demos. 🇺🇸
- [Flutter UI Challenges](https://github.com/lohanidamodar/flutter_ui_challenges) — 100+ UI screens recreated in Flutter to study layout. 🇺🇸
- [Desafios (Flutterando)](https://github.com/Flutterando/desafios) — Coding challenges proposed by the Flutterando community, in Portuguese.
- [Expo examples (oficial)](https://github.com/expo/examples) — Expo's official example projects for each SDK feature. 🇺🇸
- [react-native-template-obytes](https://github.com/obytes/react-native-template-obytes) — Production template for React Native with Expo, TypeScript and best practices. 🆕 🇺🇸
- [App Ideas Collection](https://github.com/florinpop17/app-ideas) — App ideas by difficulty level to build your portfolio. 🇺🇸
- [awesome-flutter](https://github.com/Solido/awesome-flutter) — Curated list of Flutter packages, articles and open-source apps. 🇺🇸
- [awesome-ios](https://github.com/vsouza/awesome-ios) — Curated list of the iOS ecosystem, maintained by a Brazilian. 🇺🇸
- [awesome-react-native](https://github.com/jondot/awesome-react-native) — Curated list of React Native components, tools and apps. 🇺🇸
- [kmp-awesome](https://github.com/terrakok/kmp-awesome) — Curated list of Kotlin Multiplatform libraries and tools. 🆕 🇺🇸
- [Open-source iOS apps](https://github.com/dkhamsing/open-source-ios-apps) — Collaborative list of open-source iOS apps to read production code. 🇺🇸
- [Open-source Flutter apps (open-apps)](https://github.com/tortuvshin/open-apps) — Directory of real, open-source Flutter apps. 🇺🇸
- [Empresas que usam Flutter no Brasil](https://github.com/FlutterComunidadeBR/empresas-que-usam-flutter-no-brasil) — Collaborative repository listing Brazilian companies and apps built with Flutter.

## 🤖 AI in practice
In mobile, AI moved **inside the official IDEs**: Android Studio ships with Gemini (chat, agent mode and natural-language tests) and Xcode 26 has a built-in assistant with ChatGPT, Claude and other models. At the same time, devices started running models **on-device** (Gemini Nano on Android, Foundation Models on iOS 26), which opens a new category of features for your app. Use both — with judgment.

**For learning**
- Paste the whole Gradle or Xcode build error (not just the last line) and ask: *"explain the likely cause and the minimal step to fix it"*. Build errors are the main barrier for beginners.
- Ask it to **convert** an XML layout to Jetpack Compose, a UIKit screen to SwiftUI or a React class component to a function with hooks — then ask it to explain every change.
- Ask for one exercise per concept: *"give me 3 exercises on `LazyColumn` (or `List` in SwiftUI, `ListView.builder` in Flutter, `FlatList` in RN) with answer keys"*.
- Ask it to explain the lifecycle (Activity/Composable, SwiftUI View, StatefulWidget) by drawing the flow in text, and confirm in the official docs.
- Use previews: in Compose and SwiftUI, ask for the code, paste it and see the screen without an emulator. If the preview breaks, the AI got it wrong.

**For work**
- In Android Studio, use [Gemini](https://developer.android.com/studio/gemini/overview): **Agent Mode** makes changes across multiple files and **Journeys** writes end-to-end tests in natural language. In Xcode, use the [built-in assistant](https://developer.apple.com/documentation/xcode/writing-code-with-intelligence-in-xcode). For Flutter and React Native, [Cursor](https://cursor.com/), [Copilot](https://github.com/features/copilot) or [Claude Code](https://code.claude.com/docs/en/overview) in VS Code.
- Connect the agent to your project with MCP: Flutter has the [Dart MCP server](https://docs.flutter.dev/ai/get-started) and Expo has the [Expo MCP](https://docs.expo.dev/mcp/). This reduces made-up APIs.
- Good uses: generating `data class`/`struct`/models from a JSON, writing unit and widget tests, creating accessibility strings, translating localization files, writing the store listing copy and reviewing code before the PR.
- After **every** accepted suggestion: build, run the tests, run the linter (detekt, SwiftLint, `flutter analyze`, ESLint) and test **on a real device**. Emulators don't catch permission, camera, GPS or battery problems.

**AI inside the app (on-device and cloud)**
- Start with what's ready-made: [ML Kit](https://developers.google.com/ml-kit?hl=pt-br) (OCR, barcodes, faces, translation) runs on Android and iOS without training anything.
- On-device language models: [Gemini Nano](https://developer.android.com/ai/gemini-nano) on Android and the [Foundation Models framework](https://developer.apple.com/documentation/foundationmodels) on iOS 26 — no cost per call, they work offline and data never leaves the phone.
- For your own models: [LiteRT](https://ai.google.dev/edge/litert), [Core ML](https://developer.apple.com/documentation/coreml/), [ExecuTorch](https://docs.pytorch.org/executorch/stable/index.html) or [MLC LLM](https://github.com/mlc-ai/mlc-llm).
- To call Gemini/Claude/GPT in the cloud, **never put the API key in the app** (it gets extracted in minutes): use [Firebase AI Logic](https://firebase.google.com/docs/ai-logic), the [Vercel AI SDK](https://ai-sdk.dev/docs/getting-started/expo) with your own backend, or your own proxy.

**Limits and good practices**
- AI **makes up APIs**, especially for recent versions (Compose, SwiftUI and the Expo SDK change fast). Confirm in the official docs and release notes.
- It tends to ignore lifecycle, permissions, error states and accessibility. Review each of those yourself.
- Google Play and the App Store have policies on AI-generated content and privacy; read the [review guidelines](https://developer.apple.com/app-store/review/guidelines/) and the [Play Console help](https://support.google.com/googleplay/android-developer/?hl=pt-BR) before launching.
- User data does not go into prompts without consent and without a company policy. Prefer on-device when the data is sensitive.
- Understand what you accept: in interviews and in production, the code is yours.

### AI assistants and tools for development
- [Gemini in Android Studio (oficial)](https://developer.android.com/studio/gemini/overview) — AI assistant built into Android Studio: chat, code generation, crash analysis and previews. 🆕 🇺🇸
- [Agent Mode — Android Studio](https://developer.android.com/studio/gemini/agent-mode) — Gemini agent mode that performs multi-step tasks and edits multiple files. 🆕 🇺🇸
- [Journeys — Android Studio](https://developer.android.com/studio/gemini/journeys) — End-to-end tests described in natural language and run by Gemini on the emulator. 🆕 🇺🇸
- [Writing code with intelligence in Xcode (oficial)](https://developer.apple.com/documentation/xcode/writing-code-with-intelligence-in-xcode) — Apple's documentation on the Xcode 26 assistant (ChatGPT, Claude and other models). 🆕 🇺🇸
- [JetBrains AI Assistant](https://www.jetbrains.com/ai/) — AI in IntelliJ/Android Studio (via plugin) and Fleet, with Kotlin and KMP support. 🆕 🇺🇸
- [GitHub Copilot](https://github.com/features/copilot) — Autocomplete and chat in VS Code, Xcode and Android Studio; free for students. 🆕 🇺🇸
- [Cursor](https://cursor.com/) — VS Code-based editor with built-in AI; good for Flutter and React Native. 🆕 🇺🇸
- [Claude Code](https://code.claude.com/docs/en/overview) — Terminal coding agent: refactors, writes tests and navigates native and cross-platform projects. 🆕 🇺🇸
- [Get started developing with AI (Flutter)](https://docs.flutter.dev/ai/get-started) — Flutter's official guide to using AI assistants with context rules and the Dart MCP server. 🆕 🇺🇸
- [Using MCP with Expo](https://docs.expo.dev/mcp/) — Expo's official MCP server to connect AI agents to the docs and the project. 🆕 🇺🇸
- [Firebase Studio](https://firebase.studio/) — Google's cloud environment that prototypes apps (including Flutter) from prompts. 🆕 🇺🇸

### On-device AI and SDKs for your app
- [AI on Android (oficial)](https://developer.android.com/ai) — Official Android AI hub: Gemini Nano, ML Kit, LiteRT and Firebase AI Logic. 🆕 🇺🇸
- [Gemini Nano (Android)](https://developer.android.com/ai/gemini-nano) — Google's on-device model, with APIs for summarization, rewriting and image description. 🆕 🇺🇸
- [ML Kit (PT-BR)](https://developers.google.com/ml-kit?hl=pt-br) — Ready-made vision and text APIs (OCR, barcodes, translation, faces) for Android and iOS. 🆕
- [LiteRT (antigo TensorFlow Lite)](https://ai.google.dev/edge/litert) — Google's runtime to run models on-device on Android, iOS and embedded. 🆕 🇺🇸
- [Google AI Edge Gallery](https://github.com/google-ai-edge/gallery) — Open-source app running Gemma and other LLMs 100% on-device; great to study. 🆕 🇺🇸
- [Firebase AI Logic](https://firebase.google.com/docs/ai-logic) — Use the Gemini API from your app without exposing your key, with Android, iOS, Flutter and RN SDKs. 🆕 🇺🇸
- [Foundation Models framework (Apple)](https://developer.apple.com/documentation/foundationmodels) — iOS 26 framework to use Apple Intelligence's on-device model from Swift, with structured output. 🆕 🇺🇸
- [Meet the Foundation Models framework (WWDC25)](https://developer.apple.com/videos/play/wwdc2025/286/) — Official WWDC25 session introducing the framework. 🆕 🇺🇸
- [Core ML](https://developer.apple.com/documentation/coreml/) — Apple's framework to run machine learning models on-device. 🇺🇸
- [Flutter AI Toolkit](https://docs.flutter.dev/ai/ai-toolkit) — Chat widgets and Gemini/Vertex AI integration for Flutter apps. 🆕 🇺🇸
- [Vercel AI SDK — Expo](https://ai-sdk.dev/docs/getting-started/expo) — Official guide to use the AI SDK (streaming, tools) in React Native apps with Expo. 🆕 🇺🇸
- [react-native-ai (Callstack)](https://github.com/callstackincubator/ai) — On-device LLM execution in React Native, compatible with the Vercel AI SDK. 🆕 🇺🇸
- [ExecuTorch (PyTorch)](https://docs.pytorch.org/executorch/stable/index.html) — PyTorch's runtime for on-device models on Android and iOS. 🆕 🇺🇸
- [MLC LLM](https://github.com/mlc-ai/mlc-llm) — Universal engine to run LLMs locally, with Android and iOS SDKs. 🆕 🇺🇸

## 📜 Certifications
In mobile, **certification matters less than a portfolio**: recruiters look at published apps, code on GitHub and mastery of the stack. Google **retired** the Associate Android Developer; the only Apple-linked certification is App Development with Swift (Certiport), aimed at students; Flutter and React Native have no official certification. What is useful: Google Play's **free** certificate on store listings, Meta's professional certificates on Coursera and the track certificates from Brazilian platforms, which help on a résumé.
- [App Development with Swift (Apple/Certiport)](https://certiport.pearsonvue.com/Certifications/Apple/App-Dev-With-Swift/Overview.aspx) — The only official Apple-linked certification, delivered by Certiport: Associate and Certified User levels. 💰 🇺🇸
- [Desenvolvimento de apps com Swift — certificação (Apple Brasil)](https://www.apple.com/br/education/higher-education/app-development/) — Apple's official Portuguese page explaining the education program and the App Development with Swift certification.
- [Google Play Store Listing Certificate (gratuito)](https://playacademy.withgoogle.com/certificate/) — Free Google certificate on Play Store listing and policies; online exam of up to 5 hours. 🇺🇸
- [Google Developers Certification (página oficial)](https://developers.google.com/certification) — Official page: today it lists only the Store Listing Certificate and Google Cloud certifications — the Associate Android Developer was retired. 🇺🇸
- [Meta Android Developer Professional Certificate (Coursera)](https://www.coursera.org/professional-certificates/meta-android-developer) — Meta's professional certificate in Kotlin/Android, recognized on résumés. 💰 🇺🇸
- [Meta iOS Developer Professional Certificate (Coursera)](https://www.coursera.org/professional-certificates/meta-ios-developer) — Meta's professional certificate in Swift/iOS. 💰 🇺🇸
- [Formações de Mobile da Alura (certificado)](https://www.alura.com.br/cursos-online-mobile) — Alura track certificates in Android, iOS, Flutter and React Native, recognized by Brazilian companies. 💰
- [Introdução ao Flutter (DIO) — com certificado](https://www.dio.me/courses/introducao-ao-flutter) — Free course that issues a completion certificate.
- [Curso de Flutter COMPLETO (Cursa) — com certificado](https://cursa.com.br/curso-de-flutter-completo/513) — Free digital certificate upon completing Flutterando's course.

## 💼 Career and jobs
Mobile jobs in Brazil concentrate in banks and fintechs (Nubank, Itaú, PicPay, Inter), retail, healthcare and consultancies, with a strong presence of Kotlin, Swift, Flutter and React Native. The most common titles are *Android Developer*, *iOS Developer*, *Mobile Developer* (cross-platform) and, increasingly, *KMP*. Salaries vary a lot by seniority and city — use the sources below as a reference, not a rule. Tip: in the GitHub job repositories, search open issues for "Flutter", "Kotlin" or "Swift".
- [Guia Salarial 2026 (Robert Half)](https://www.roberthalf.com/br/pt/insights/guia-salarial) — Annual salary survey with ranges for mobile developers in Brazil by seniority. 🆕
- [Desenvolvedor Mobile — Salário Brasil (salario.com.br)](https://www.salario.com.br/profissao/desenvolvedor-mobile-cbo-317110/) — Official average salary (CAGED data) by company size, state and level.
- [Stack Overflow Developer Survey 2025](https://survey.stackoverflow.co/2025/) — Global survey with salaries and usage of Kotlin, Swift, Dart, Flutter and React Native. 🆕 🇺🇸
- [Programathor — vagas Mobile](https://programathor.com.br/jobs-mobile) — Tech jobs in Brazil filtered by mobile.
- [Programathor — vagas Flutter](https://programathor.com.br/jobs-flutter) — Flutter jobs in Brazil.
- [Programathor — vagas React Native](https://programathor.com.br/jobs-react-native) — React Native jobs in Brazil.
- [androiddevbr/vagas](https://github.com/androiddevbr/vagas) — Android job board from the Brazilian community, as GitHub issues.
- [CocoaHeadsBrasil/vagas](https://github.com/CocoaHeadsBrasil/vagas) — iOS and macOS jobs posted by the Brazilian community.
- [flutterbr/vagas](https://github.com/flutterbr/vagas) — Flutter and Dart jobs on GitHub.
- [react-brasil/vagas](https://github.com/react-brasil/vagas) — React and React Native jobs on GitHub.
- [Flutterando — Vagas e oportunidades](https://github.com/Flutterando/forum/discussions/categories/vagas-e-oportunidades) — Jobs category in the Flutterando community discussions.
- [Github Vagas Brasil](https://githubvagasbrasil.vercel.app/) — Aggregator gathering jobs from the Brazilian repositories (Android, iOS, Flutter, React) in one place.
- [GeekHunter](https://www.geekhunter.com/pt) — Brazilian platform where companies make offers to developers.
- [Coodesh](https://coodesh.com/) — Tech jobs in Brazil with standardized selection processes.
- [Remotar](https://remotar.com.br/) — 100% remote jobs for Brazilians.
- [Tech Interview Handbook](https://www.techinterviewhandbook.org/) — Complete preparation for technical interviews. 🇺🇸
- [Android Interview Questions](https://github.com/amitshekhariitbhu/android-interview-questions) — Frequently asked Android interview questions, by topic. 🇺🇸
- [iOS Interview Questions](https://github.com/onthecodepath/iOS-Interview-Questions) — iOS interview questions with answers. 🇺🇸

## 👥 Communities
- [Flutterando (Discord)](https://discord.com/invite/flutterando-509072164666867753) — Brazil's largest Flutter community, with thousands of members and channels by topic.
- [Flutter Brasil (Discord)](https://discord.com/invite/XCsGvD6sw7) — Brazilian Flutter community for questions, career and experience sharing.
- [Flutterando — fórum no GitHub](https://github.com/Flutterando/forum) — Discussions, jobs and architecture organized in GitHub Discussions.
- [Flutter Brasil (Telegram)](https://t.me/flutterbrasil) — Brazilian Flutter group on Telegram.
- [Android Dev BR (Telegram)](https://t.me/androiddevbr) — Brazil's largest Android community; also on GitHub and YouTube.
- [Kotlin Brasil (Telegram)](https://t.me/kotlinbr) — Brazilian Kotlin, Android and KMP group.
- [Comunidade Kotlin Brasil — Telegram, Discord e eventos](https://kotlin.dev.br/comunidade/) — Page centralizing all Kotlin community groups and events in Brazil. 🆕
- [Swift BR (Telegram)](https://t.me/swiftbr) — Brazilian Swift and iOS group on Telegram.
- [CocoaHeads Brasil (GitHub)](https://github.com/CocoaHeadsBrasil) — Brazilian iOS/macOS community with meetups in several cities and a job board.
- [Google Developer Groups (PT-BR)](https://developers.google.com/community?hl=pt-br) — GDGs and Google events in Brazil (DevFest, I/O Extended), with lots of Android and Flutter content.
- [He4rt Developers](https://heartdevs.com/) — Brazilian open-source community with an active Discord and mobile channels.
- [Desenvolvedores Brasil (Discord)](https://discord.com/invite/t3vYGUuK6P) — Brazilian community with tips, courses, mentoring and job posts.
- [Lista de grupos de tecnologia no Telegram (TI-Brasil)](https://github.com/TI-Brasil/lista-telegram-brasil) — Directory of Brazilian Telegram groups, including Android, iOS and Flutter.
- [Flutter Community (oficial)](https://flutter.dev/community) — Official page with Discord, forums and Flutter groups worldwide. 🇺🇸
- [Kotlin Community (oficial)](https://kotlinlang.org/community/) — Official Kotlin Slack (#android, #multiplatform channels), forums and KUGs. 🇺🇸
- [Swift Forums (oficial)](https://forums.swift.org/) — Official Swift language forum, where language evolution is discussed. 🇺🇸
- [Apple Developer Forums](https://developer.apple.com/forums/) — Apple's official forum with answers from Apple engineers. 🇺🇸
- [Expo Developers (Discord)](https://discord.com/invite/expo) — Official Expo and React Native Discord. 🇺🇸
- [r/androiddev](https://www.reddit.com/r/androiddev/) — Android development subreddit. 🇺🇸
- [r/iOSProgramming](https://www.reddit.com/r/iOSProgramming/) — iOS development subreddit. 🇺🇸
- [r/FlutterDev](https://www.reddit.com/r/FlutterDev/) — Flutter subreddit. 🇺🇸
- [r/reactnative](https://www.reddit.com/r/reactnative/) — React Native subreddit. 🇺🇸

## 🚨 How to contribute
Found a broken link, a new course or a tool that deserves to be here? Open an issue using the repository templates or send a pull request. Criteria: working link, legal content that is free or clearly marked as paid, with a one-line description. Details in [CONTRIBUTING.md](../CONTRIBUTING.md).

## 📄 License
This project is under the [MIT](../LICENSE) license. Made with 💙 by [Arthur Coutinho (@arthurspk)](https://github.com/arthurspk) and the [Guia Dev Brasil](https://github.com/arthurspk/guiadevbrasil) community.

## 💙 Support the project
Star this repository and the [main guide](https://github.com/arthurspk/guiadevbrasil), share it with someone who is starting out and follow the project on social media:

[<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">](https://github.com/arthurspk)
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">](https://www.linkedin.com/in/arthurspk/)
[<img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X (Twitter)">](https://x.com/manotoquinho)
[<img src="https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">](https://www.instagram.com/arthurspk/)
[<img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook">](https://www.facebook.com/seixasqlc/)
