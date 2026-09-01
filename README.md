<p align="center">
  <a href="https://github.com/arthurspk/guiadevbrasil">
    <img src="./images/guia.png" alt="Guia Dev Brasil" width="160" height="160">
  </a>
  <h1 align="center">Guia de Mobile</h1>
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/arthurspk/guiadomobile?style=flat-square" alt="Stars">
  <img src="https://img.shields.io/github/forks/arthurspk/guiadomobile?style=flat-square" alt="Forks">
  <img src="https://img.shields.io/github/last-commit/arthurspk/guiadomobile?style=flat-square" alt="Último commit">
  <img src="https://img.shields.io/github/license/arthurspk/guiadomobile?style=flat-square" alt="Licença">
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square" alt="PRs Welcome">
</p>

> Guia completo de Mobile: trilhas, cursos, livros, canais, ferramentas e comunidades
> para você entrar e evoluir na área. Última revisão: setembro/2026.

## 🌍 Idiomas
🇧🇷 Português (você está aqui) · [🇺🇸 English](./translations/README.en.md)

## 📚 Sumário
- [🎯 Sobre este guia](#-sobre-este-guia)
- [🗺️ Roadmap](#-roadmap)
- [🚀 Por onde começar](#-por-onde-começar)
- [🎓 Cursos gratuitos](#-cursos-gratuitos)
- [💰 Cursos pagos](#-cursos-pagos)
- [📖 Documentação e apostilas](#-documentação-e-apostilas)
- [📚 Livros](#-livros)
- [🎥 Canais no YouTube](#-canais-no-youtube)
- [🎙️ Podcasts](#-podcasts)
- [📰 Sites, blogs e newsletters](#-sites-blogs-e-newsletters)
- [🛠️ Ferramentas](#-ferramentas)
- [🧪 Projetos práticos e desafios](#-projetos-práticos-e-desafios)
- [🤖 IA na prática](#-ia-na-prática)
- [📜 Certificações](#-certificações)
- [💼 Carreira e vagas](#-carreira-e-vagas)
- [👥 Comunidades](#-comunidades)
- [🚨 Como contribuir](#-como-contribuir)
- [📄 Licença](#-licença)
- [💙 Apoie o projeto](#-apoie-o-projeto)

## 🎯 Sobre este guia
Desenvolvimento **mobile** é criar aplicativos para celulares e tablets — hoje, na prática, para **Android** e **iOS**, que juntos dominam o mercado. Existem dois caminhos: o **nativo** (Kotlin + Jetpack Compose no Android; Swift + SwiftUI no iOS), que dá acesso total à plataforma, e o **multiplataforma** (Flutter, React Native, Kotlin Multiplatform), em que um único código gera apps para os dois sistemas. O Brasil é um dos maiores mercados de apps do mundo, e bancos, fintechs, varejo e startups contratam para todas essas stacks.

Este guia é para quem quer entrar na área ou se especializar. Ele cobre as quatro stacks principais a partir da **documentação oficial**, além de publicação nas lojas, IA no fluxo de trabalho, certificações, salários e vagas. Os recursos em **português e gratuitos** vêm primeiro em cada seção; 💰 marca conteúdo pago, 🇺🇸 conteúdo em inglês e 🆕 material publicado ou atualizado entre 2024 e 2026. Todo link foi verificado na data da última revisão.

## 🗺️ Roadmap
- [roadmap.sh — Android Developer](https://roadmap.sh/android) — Roadmap visual da comunidade para Android nativo: Kotlin, Compose, arquitetura, testes e publicação. 🇺🇸
- [roadmap.sh — iOS Developer](https://roadmap.sh/ios) — Roadmap visual para iOS: Swift, SwiftUI/UIKit, persistência, redes e App Store. 🇺🇸
- [roadmap.sh — Flutter](https://roadmap.sh/flutter) — Roadmap visual de Flutter: Dart, widgets, estado, pacotes e deploy. 🇺🇸
- [roadmap.sh — React Native](https://roadmap.sh/react-native) — Roadmap visual de React Native: JavaScript/TypeScript, React, Expo, navegação e módulos nativos. 🇺🇸
- [Android Developer Roadmap (skydoves)](https://github.com/skydoves/android-developer-roadmap) — Roadmap em imagem e texto, mantido por um Google Developer Expert, com os temas em ordem de prioridade. 🇺🇸
- [iOS Developer Roadmap (BohdanOrlov)](https://github.com/BohdanOrlov/iOS-Developer-Roadmap) — Árvore de conhecimento de iOS com links para cada tópico, do básico ao avançado. 🇺🇸
- [Apple Developer Pathways](https://developer.apple.com/pathways/) — Trilhas oficiais da Apple (Swift, SwiftUI, App Store, design) que organizam documentação, vídeos e tutoriais em ordem. 🆕 🇺🇸
- [Learn Flutter (oficial)](https://docs.flutter.dev/learn) — Página oficial que reúne trilha, codelabs, vídeos e cursos recomendados para aprender Flutter. 🇺🇸
- [Kotlin Multiplatform — recursos de aprendizado (oficial)](https://kotlinlang.org/docs/multiplatform/kmp-learning-resources.html) — Lista oficial da JetBrains com tutoriais, exemplos e cursos para aprender KMP e Compose Multiplatform. 🆕 🇺🇸

**Trilha resumida** (siga na ordem; cada etapa tem recursos nas seções abaixo):

1. **Fundamentos** — lógica de programação, Git, HTTP/JSON e **uma** linguagem: Kotlin (Android), Swift (iOS), Dart (Flutter) ou JavaScript/TypeScript (React Native).
2. **Escolha a plataforma** — nativo (Android ou iOS) ou multiplataforma (Flutter, React Native, KMP). Não tente aprender tudo de uma vez: domine uma stack e migre depois, se precisar.
3. **UI declarativa** — Jetpack Compose, SwiftUI, widgets do Flutter ou componentes do React Native: layout, listas, navegação, temas, dark mode e acessibilidade.
4. **Estado e arquitetura** — fluxo de dados unidirecional, ViewModel/`@Observable`/Riverpod/Zustand, injeção de dependência e separação em camadas (UI, domínio, dados).
5. **Dados** — consumo de APIs REST (Retrofit/Ktor, URLSession, dio, fetch), persistência local (Room, SwiftData, Drift, SQLite) e backend gerenciado (Firebase, Supabase).
6. **Qualidade** — testes unitários e de UI, offline-first, performance, segurança (OWASP MAS) e permissões.
7. **Publicação** — assinatura, App Bundle/IPA, Google Play Console, App Store Connect, TestFlight, CI/CD (fastlane, Codemagic, GitHub Actions) e políticas das lojas.
8. **Avançado** — Kotlin Multiplatform e Compose Multiplatform, IA on-device (Gemini Nano, Foundation Models, LiteRT), monetização, analytics e módulos nativos.

## 🚀 Por onde começar
1. **Escolha uma stack e olhe o mapa.** Compare os roadmaps de [Android](https://roadmap.sh/android), [iOS](https://roadmap.sh/ios), [Flutter](https://roadmap.sh/flutter) e [React Native](https://roadmap.sh/react-native). Sem Mac? Comece por Android, Flutter ou React Native — compilar para iOS exige macOS.
2. **Aprenda a linguagem antes do framework:** [Tour of Kotlin](https://kotlinlang.org/docs/kotlin-tour-welcome.html), [Swift — Getting Started](https://www.swift.org/getting-started/), [Dart](https://dart.dev/language) ou [JavaScript na MDN (PT-BR)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript). E [Git](https://git-scm.com/book/pt-br/v2) desde o primeiro dia.
3. **Instale o ambiente:** [Android Studio](https://developer.android.com/studio?hl=pt-br), [Xcode](https://developer.apple.com/xcode/) (só no Mac), [Flutter SDK](https://docs.flutter.dev/install) ou [Expo](https://docs.expo.dev/get-started/create-a-project/) para React Native.
4. **Experimente sem instalar nada:** [Kotlin Playground](https://play.kotlinlang.org/), [Swift Playground](https://developer.apple.com/swift-playground/), [DartPad](https://dartpad.dev/) e [Expo Snack](https://snack.expo.dev/).
5. **Faça o curso oficial da sua stack:** [Noções básicas do Android com o Compose (PT-BR)](https://developer.android.com/courses/android-basics-compose/course?hl=pt-br), [Develop in Swift Tutorials](https://developer.apple.com/tutorials/develop-in-swift/), [Flutter learning pathway](https://docs.flutter.dev/learn/pathway) ou o [tutorial do Expo](https://docs.expo.dev/tutorial/introduction/).
6. **Complemente com um curso em português:** [Alex Felipe (Compose)](https://www.youtube.com/playlist?list=PLYaQbIm_3oZ9BwznyXn7n_Zl1KBq3I9oO), [Portal Hugo Cursos (Swift)](https://www.youtube.com/playlist?list=PLxNM4ef1BpxjjMKpcYSqXI4eY4tZG2csm), [Flutterando (Flutter)](https://www.youtube.com/playlist?list=PLlBnICoI-g-d-J57QIz6Tx5xtUDGQdBFB) ou [DevClub (React Native + Expo)](https://www.youtube.com/watch?v=a8YvzTXft9c).
7. **Construa dois ou três apps de verdade** — lista de tarefas com persistência, app de clima consumindo API, catálogo com login — usando o [App Ideas](https://github.com/florinpop17/app-ideas) e os [Desafios da Flutterando](https://github.com/Flutterando/desafios). Publique o código no GitHub com README e prints.
8. **Publique um app nas lojas.** Siga o [checklist de lançamento do Google Play](https://developer.android.com/distribute/best-practices/launch/launch-checklist) e as [diretrizes de revisão da App Store](https://developer.apple.com/app-store/review/guidelines/). Um app publicado vale mais que dez certificados na entrevista.

Seu primeiro app em 2 minutos (Flutter):

```bash
flutter doctor                      # confere SDK, Android Studio/Xcode e dispositivos
flutter create ola_mobile && cd ola_mobile
flutter run                         # roda no emulador ou no celular conectado
```

E o "Olá, mundo" em Jetpack Compose (Android nativo):

```kotlin
@Composable
fun Saudacao(nome: String) {
    Text(text = "Olá, $nome!")
}

@Preview(showBackground = true)
@Composable
fun SaudacaoPreview() {
    Saudacao("Guia Dev Brasil")   // aparece no preview do Android Studio, sem emulador
}
```

## 🎓 Cursos gratuitos
### Em português
- [Noções básicas do Android com o Compose (Google, PT-BR)](https://developer.android.com/courses/android-basics-compose/course?hl=pt-br) — Curso oficial e gratuito do Google, traduzido, que ensina Kotlin e Jetpack Compose do zero com projetos por unidade. 🆕
- [Jetpack Compose para desenvolvedores Android (Google, PT-BR)](https://developer.android.com/courses/jetpack-compose/course?hl=pt-br) — Curso oficial para quem já programa Android e quer migrar de XML para Compose. 🆕
- [Codelabs do Android (PT-BR)](https://developer.android.com/get-started/codelabs?hl=pt-br) — Tutoriais guiados e gratuitos do Google, muitos traduzidos, cobrindo Compose, arquitetura, Room, testes e mais.
- [Iniciante em Android com Jetpack Compose (Alex Felipe)](https://www.youtube.com/playlist?list=PLYaQbIm_3oZ9BwznyXn7n_Zl1KBq3I9oO) — Playlist gratuita de um ex-instrutor da Alura, construindo um app Android com Compose passo a passo.
- [Curso de Jetpack Compose com Kotlin: Iniciantes (Android — Simples e Direto)](https://www.youtube.com/watch?v=g7TDiEDTReM) — Aula longa e direta para o primeiro contato com Compose, sem pressupor experiência em Android.
- [Curso de Swift — Desenvolvimento iOS Apple (Portal Hugo Cursos)](https://www.youtube.com/playlist?list=PLxNM4ef1BpxjjMKpcYSqXI4eY4tZG2csm) — Playlist em português com dezenas de aulas curtas sobre a linguagem Swift e o Xcode.
- [Aprenda Swift — lista de conteúdos (Codando Apple)](https://github.com/CodandoApple/aprenda-swift) — Repositório brasileiro com materiais gratuitos organizados para aprender Swift, SwiftUI e iOS.
- [Curso grátis Swift e SwiftUI — Stanford CS193p (curadoria de Filipe Deschamps)](https://www.youtube.com/playlist?list=PLMdYygf53DP46rneFgJ7Ab6fJPcMvr8gC) — Playlist com as aulas do curso de iOS de Stanford (em inglês) e vídeo de apresentação em português explicando como acompanhar. 🇺🇸
- [Curso COMPLETO de Flutter (Flutterando)](https://www.youtube.com/playlist?list=PLlBnICoI-g-d-J57QIz6Tx5xtUDGQdBFB) — Curso da maior comunidade Flutter do Brasil, do Dart básico à publicação.
- [Curso de Flutter COMPLETO — Cursa (Flutterando, com certificado)](https://cursa.com.br/curso-de-flutter-completo/513) — Mesmo conteúdo da Flutterando organizado em plataforma gratuita que emite certificado; atualizado em 2024. 🆕
- [Curso Flutter Básico [NV1] (Deivid Willyan)](https://www.youtube.com/playlist?list=PLRpTFz5_57cvo0CHf-AnojOvpznz8YO7S) — Primeiro nível de uma série gratuita, muito didática, sobre widgets, layouts e navegação.
- [Curso Gratuito de Flutter 2024 (AbnerCasalloTECH)](https://www.youtube.com/playlist?list=PLHgdJafeca0nFak4Jj1aKXglmswsPbE1b) — Playlist recente em português cobrindo Flutter 3 e Dart moderno. 🆕
- [Curso de Flutter e Dart (daves tecnologia)](https://www.youtube.com/playlist?list=PL5EmR7zuTn_aX0pG4oWTyKKQT25Hkq2XG) — Curso gratuito, um conceito por vídeo, começando pela linguagem Dart.
- [Introdução ao Flutter (DIO)](https://www.dio.me/courses/introducao-ao-flutter) — Curso gratuito da DIO com certificado para o primeiro contato com Flutter.
- [Primeiros Passos com React Native & Expo (DIO)](https://www.dio.me/courses/primeiros-passos-com-react-native-expo) — Curso gratuito com certificado: ambiente, Expo e primeiro app.
- [Curso completo de React Native + Expo — do zero (DevClub)](https://www.youtube.com/watch?v=a8YvzTXft9c) — Aula única e completa, publicada em 2025, criando um app para iPhone e Android com Expo. 🆕
- [Curso de React Native + Expo (Jovem Programador)](https://www.youtube.com/playlist?list=PLqfQXYWB7zobw0ruLOoeAKCCc7_jQo-JN) — Playlist em português com o fluxo moderno do Expo, aula a aula.
- [Curso de React Native — app iOS e Android (Portal Hugo Cursos)](https://www.youtube.com/playlist?list=PLxNM4ef1Bpxhe_PxwprF0R2fp0UurDZuw) — Série de aulas curtas em português cobrindo componentes, estilos e navegação.
- [Kotlin Multiplatform — curso do zero ao avançado (CodandoTV)](https://www.youtube.com/watch?v=2_dYJr1s5Ak) — Curso em português publicado em 2025 sobre KMP e Compose Multiplatform: um código para Android e iOS. 🆕
- [Apple Developer Academy — Mackenzie (São Paulo)](https://developeracademy.mackenzie.br/) — Programa gratuito de dois anos da Apple com a universidade; processo seletivo para a turma 2027/2028. 🆕
- [Apple Developer Academy — IFCE (Fortaleza)](https://developeracademy.ifce.edu.br/) — Polo da Apple Developer Academy no Ceará, gratuito, focado em desenvolvimento iOS e design de apps. 🆕
- [Apple Developer Academies (página oficial da Apple)](https://developer.apple.com/academies/) — Lista oficial de todas as academias no mundo, incluindo os polos brasileiros. 🇺🇸
- [Learn X in Y minutes — Kotlin (PT-BR)](https://learnxinyminutes.com/pt-br/kotlin/) — Toda a sintaxe do Kotlin em um arquivo comentado, em português.
- [Learn X in Y minutes — Swift (PT-BR)](https://learnxinyminutes.com/pt-br/swift/) — Toda a sintaxe do Swift em um arquivo comentado, em português.
- [Learn X in Y minutes — Dart (PT-BR)](https://learnxinyminutes.com/pt-br/dart/) — Toda a sintaxe do Dart em um arquivo comentado, em português.

### Em inglês
- [Develop in Swift Tutorials (Apple)](https://developer.apple.com/tutorials/develop-in-swift/) — Tutoriais oficiais e atuais da Apple para aprender Swift e SwiftUI construindo apps reais no Xcode. 🆕 🇺🇸
- [Introducing SwiftUI (Apple)](https://developer.apple.com/tutorials/swiftui/) — Tutorial oficial clássico da Apple: um app completo de pontos de interesse com SwiftUI. 🇺🇸
- [Develop apps for Apple platforms (Apple)](https://developer.apple.com/tutorials/app-dev-training/) — Curso oficial com o app Scrumdinger: SwiftUI, dados, áudio e persistência. 🇺🇸
- [Learning SwiftUI (Apple)](https://developer.apple.com/tutorials/swiftui-concepts) — Conceitos de SwiftUI explicados com exemplos curtos: layout, estado, navegação e animação. 🇺🇸
- [100 Days of SwiftUI (Hacking with Swift)](https://www.hackingwithswift.com/100/swiftui) — Curso gratuito de 100 dias de Paul Hudson, com projetos e testes diários; o mais recomendado para SwiftUI. 🇺🇸
- [CS193p — Developing Apps for iOS (Stanford)](https://cs193p.stanford.edu/) — Curso de iOS de Stanford com aulas em vídeo gratuitas sobre Swift e SwiftUI. 🇺🇸
- [Tour of Kotlin (oficial)](https://kotlinlang.org/docs/kotlin-tour-welcome.html) — Tour oficial e interativo pela linguagem Kotlin, com exercícios rodando no navegador. 🆕 🇺🇸
- [Kotlin Koans](https://kotlinlang.org/docs/koans.html) — Exercícios oficiais para aprender a sintaxe e os idiomas do Kotlin resolvendo testes que falham. 🇺🇸
- [Get started with Kotlin Multiplatform (oficial)](https://kotlinlang.org/docs/multiplatform/get-started.html) — Tutorial oficial da JetBrains: primeiro app Android + iOS compartilhando código Kotlin. 🆕 🇺🇸
- [Create your Compose Multiplatform app (oficial)](https://kotlinlang.org/docs/multiplatform/compose-multiplatform-create-first-app.html) — Tutorial oficial de UI compartilhada com Compose Multiplatform para Android, iOS e desktop. 🆕 🇺🇸
- [Flutter learning pathway (oficial)](https://docs.flutter.dev/learn/pathway) — Trilha oficial do Flutter: fundamentos, codelab do primeiro app e próximos passos. 🆕 🇺🇸
- [Google Codelabs — Flutter](https://codelabs.developers.google.com/?product=flutter) — Codelabs oficiais do Google filtrados por Flutter: layouts, animações, Firebase, testes. 🇺🇸
- [Introduction to Flutter Development with Dart (The App Brewery)](https://www.appbrewery.com/p/intro-to-flutter) — Curso gratuito da Angela Yu, feito em parceria com o Google, para iniciantes em Flutter. 🇺🇸
- [Expo Tutorial — Using React Native and Expo (oficial)](https://docs.expo.dev/tutorial/introduction/) — Tutorial oficial do Expo: um app completo com câmera, gestos e publicação. 🆕 🇺🇸
- [React Native Express](https://www.reactnative.express/) — Guia interativo e gratuito que percorre React Native com exemplos executáveis. 🇺🇸
- [Flutter Course for Beginners — 37 horas (freeCodeCamp)](https://www.youtube.com/watch?v=VPvVD8t02U8) — Curso completo em vídeo, do Dart ao app publicado. 🇺🇸
- [Learn Kotlin Programming — Full Course (freeCodeCamp)](https://www.youtube.com/watch?v=EExSSotojVI) — Curso completo de Kotlin para quem está começando. 🇺🇸
- [Swift Programming Tutorial — Full Course (Sean Allen)](https://www.youtube.com/watch?v=CwA1VWP0Ldw) — Curso de Swift para iniciantes absolutos, direto ao ponto. 🇺🇸
- [Master React Native 2024 — Expo Router, TypeScript, Zustand (HuXn WebDev)](https://www.youtube.com/watch?v=a_SthPXtV6c) — Curso longo e atual com a stack moderna do React Native. 🆕 🇺🇸
- [React Native Full Course 2026 — Build a Mobile App Using Expo (PedroTech)](https://www.youtube.com/watch?v=RdJhqaOIWn0) — Curso recente construindo um app completo com Expo. 🆕 🇺🇸

## 💰 Cursos pagos
- [Formação Desenvolva seu primeiro app Android com Kotlin (Alura)](https://www.alura.com.br/formacao-android-kotlin) — Trilha da Alura do Android Studio ao primeiro app com Compose; certificado reconhecido no mercado brasileiro. 💰
- [Formação Evolua apps Android com Jetpack Compose (Alura)](https://www.alura.com.br/formacao-jetpack-compose-criando-telas-gerenciando-estados) — Continuação: telas, estado, ViewModel e StateFlow com Compose. 💰
- [Formação Domine a linguagem Swift (Alura)](https://www.alura.com.br/formacao-domine-linguagem-swift) — Trilha da Alura para aprender Swift e dar os primeiros passos em iOS. 💰
- [Carreira Desenvolvimento Mobile com Flutter (Alura)](https://www.alura.com.br/carreiras/desenvolvimento-mobile-com-flutter) — Trilha de carreira completa de Flutter na Alura, do Dart à publicação. 💰
- [Formação React Native (Rocketseat)](https://www.rocketseat.com.br/formacao/react-native) — Formação da Rocketseat com projetos práticos em React Native e Expo. 💰
- [Academia do Flutter (Rodrigo Rahman)](https://academiadoflutter.com.br/) — Curso completo e conhecido de Dart e Flutter em português, com foco em projetos reais. 💰
- [Meta Android Developer Professional Certificate (Coursera)](https://www.coursera.org/professional-certificates/meta-android-developer) — Programa da Meta em Kotlin e Android com certificado profissional; auditoria gratuita das aulas. 💰 🇺🇸
- [Meta iOS Developer Professional Certificate (Coursera)](https://www.coursera.org/professional-certificates/meta-ios-developer) — Programa da Meta em Swift e iOS com certificado profissional. 💰 🇺🇸
- [Meta React Native Specialization (Coursera)](https://www.coursera.org/specializations/meta-react-native) — Especialização da Meta em React Native, da fundação ao projeto final. 💰 🇺🇸
- [Hacking with Swift+](https://www.hackingwithswift.com/plus) — Assinatura de Paul Hudson com tutoriais avançados de Swift e SwiftUI. 💰 🇺🇸
- [PL Coding (Philipp Lackner)](https://www.pl-coding.com/) — Cursos de Android e KMP nível indústria, do criador de um dos maiores canais de Android. 🆕 💰 🇺🇸

## 📖 Documentação e apostilas
### Android (Kotlin e Jetpack Compose)
- [Android Developers — documentação](https://developer.android.com/docs) — Portal oficial de documentação do Android: guias, referência de API e amostras. 🇺🇸
- [Primeiros passos com o Jetpack Compose (PT-BR)](https://developer.android.com/develop/ui/compose/documentation?hl=pt-br) — Documentação oficial do Compose traduzida: layout, estado, navegação, animação e testes.
- [Kotlin e Android (PT-BR)](https://developer.android.com/kotlin?hl=pt-br) — Por que Kotlin é a linguagem oficial do Android, com guias e amostras em português.
- [Guide to app architecture](https://developer.android.com/topic/architecture) — Guia oficial de arquitetura: camadas de UI, domínio e dados, fluxo unidirecional e ViewModel. 🇺🇸
- [State and Jetpack Compose](https://developer.android.com/develop/ui/compose/state) — Como o estado funciona no Compose: hoisting, remember, ViewModel e recomposição. 🇺🇸
- [Room — banco de dados local](https://developer.android.com/training/data-storage/room) — Biblioteca oficial de persistência sobre SQLite, com Kotlin coroutines e Flow. 🇺🇸
- [Kotlin coroutines on Android](https://developer.android.com/kotlin/coroutines) — Guia oficial de concorrência no Android com coroutines e Flow. 🇺🇸
- [Android Jetpack](https://developer.android.com/jetpack) — Conjunto oficial de bibliotecas (Compose, Navigation, Room, WorkManager, Hilt) que toda equipe usa. 🇺🇸
- [Kotlin Docs (oficial)](https://kotlinlang.org/docs/home.html) — Documentação oficial da linguagem Kotlin, com referência e guias por plataforma. 🇺🇸
- [Material Design 3](https://m3.material.io/) — Sistema de design oficial do Google: componentes, cores dinâmicas, tipografia e diretrizes. 🇺🇸
- [Build accessible apps](https://developer.android.com/guide/topics/ui/accessibility) — Guia oficial de acessibilidade no Android: TalkBack, rótulos, contraste e áreas de toque. 🇺🇸
- [Security checklist (Android)](https://developer.android.com/privacy-and-security/security-tips) — Lista oficial de práticas de segurança: permissões, armazenamento, rede e criptografia. 🇺🇸

### iOS (Swift e SwiftUI)
- [Apple Developer Documentation](https://developer.apple.com/documentation/) — Portal oficial de documentação de todos os frameworks da Apple. 🇺🇸
- [SwiftUI (documentação oficial)](https://developer.apple.com/documentation/swiftui/) — Referência oficial do SwiftUI: views, layout, navegação, dados e animação. 🇺🇸
- [The Swift Programming Language (livro oficial)](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/) — Livro oficial e gratuito da linguagem Swift, sempre atualizado com a versão corrente. 🇺🇸
- [Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/) — Diretrizes oficiais de design da Apple para iOS, iPadOS, watchOS, macOS e visionOS. 🇺🇸
- [SwiftData](https://developer.apple.com/documentation/swiftdata) — Framework moderno de persistência da Apple, integrado ao SwiftUI e ao Swift concurrency. 🇺🇸
- [Apple Design Resources](https://developer.apple.com/design/resources/) — Kits oficiais de UI para Figma e Sketch, fontes SF e templates de ícones. 🇺🇸
- [Accessibility (Apple)](https://developer.apple.com/documentation/accessibility) — Documentação oficial de acessibilidade: VoiceOver, Dynamic Type e auditoria no Xcode. 🇺🇸
- [Xcode (documentação)](https://developer.apple.com/documentation/xcode) — Documentação oficial do Xcode: projetos, simulador, testes, previews e distribuição. 🇺🇸

### Multiplataforma (Flutter, React Native, Kotlin Multiplatform)
- [Flutter Brasil — documentação em português](https://flutterbrasil.dev/) — Tradução comunitária e oficial do site do Flutter para português, com docs e guias. 🆕
- [Flutter documentation (oficial)](https://docs.flutter.dev/) — Documentação oficial do Flutter: instalação, widgets, estado, testes, deploy e performance. 🇺🇸
- [Dart documentation (oficial)](https://dart.dev/docs) — Documentação oficial da linguagem Dart, com o guia de linguagem e as bibliotecas centrais. 🇺🇸
- [Flutter — Widget catalog](https://docs.flutter.dev/ui/widgets) — Catálogo oficial de widgets por categoria (Material, Cupertino, layout, entrada). 🇺🇸
- [Flutter — State management](https://docs.flutter.dev/data-and-backend/state-mgmt/intro) — Introdução oficial ao gerenciamento de estado e às opções (Provider, Riverpod, Bloc). 🇺🇸
- [Flutter for Android developers](https://docs.flutter.dev/flutter-for/android-devs) — Guia oficial de transição para quem já sabe Android nativo. 🇺🇸
- [Flutter for React Native developers](https://docs.flutter.dev/flutter-for/react-native-devs) — Guia oficial de transição para quem vem do React Native. 🇺🇸
- [React Native — documentação (oficial)](https://reactnative.dev/docs/getting-started) — Documentação oficial do React Native: componentes, APIs nativas, Nova Arquitetura e publicação. 🇺🇸
- [Expo Documentation (oficial)](https://docs.expo.dev/) — Documentação do Expo, o framework recomendado pelo time do React Native: SDK, EAS e Expo Router. 🆕 🇺🇸
- [Expo Router](https://docs.expo.dev/router/introduction/) — Navegação baseada em arquivos para React Native, com deep links e web. 🆕 🇺🇸
- [Kotlin Multiplatform (oficial)](https://kotlinlang.org/multiplatform/) — Página oficial do KMP: compartilhe lógica (e UI, com Compose Multiplatform) entre Android, iOS, web e desktop. 🆕 🇺🇸
- [Compose Multiplatform (oficial)](https://kotlinlang.org/compose-multiplatform/) — UI declarativa da JetBrains para Android, iOS (estável desde 2025), desktop e web. 🆕 🇺🇸
- [Kotlin Multiplatform Wizard](https://kmp.jetbrains.com/) — Gerador oficial de projetos KMP: escolha as plataformas e baixe o esqueleto pronto. 🆕 🇺🇸
- [O que é .NET MAUI? (Microsoft Learn, PT-BR)](https://learn.microsoft.com/pt-br/dotnet/maui/what-is-maui?view=net-maui-10.0) — Documentação em português do framework multiplataforma da Microsoft em C#.
- [Capacitor](https://capacitorjs.com/) — Runtime nativo para transformar apps web em apps iOS e Android com acesso a APIs nativas. 🇺🇸
- [Firebase — documentação (PT-BR)](https://firebase.google.com/docs?hl=pt-br) — Documentação em português do backend mais usado em apps mobile: auth, Firestore, push, Crashlytics.

### Publicação nas lojas e segurança
- [Publish your app (Android Studio)](https://developer.android.com/studio/publish) — Guia oficial: assinatura, App Bundle, versões e preparação para o Google Play. 🇺🇸
- [Launch checklist (Google Play)](https://developer.android.com/distribute/best-practices/launch/launch-checklist) — Checklist oficial de lançamento: políticas, testes, listagem, preço e distribuição. 🇺🇸
- [Ajuda do Play Console (PT-BR)](https://support.google.com/googleplay/android-developer/?hl=pt-BR) — Central de ajuda oficial em português: conta de desenvolvedor, políticas, lançamentos e monetização.
- [Preparar e lançar uma versão (Play Console, PT-BR)](https://support.google.com/googleplay/android-developer/answer/9859348?hl=pt-BR) — Passo a passo oficial em português para criar e lançar uma versão no Google Play.
- [Google Play Academy](https://playacademy.withgoogle.com/) — Cursos gratuitos do Google sobre Play Console, políticas, listagem e monetização, com certificado. 🇺🇸
- [App Review Guidelines (App Store)](https://developer.apple.com/app-store/review/guidelines/) — Regras oficiais de revisão da App Store; leia antes de submeter para evitar rejeições. 🇺🇸
- [Submitting to the App Store](https://developer.apple.com/app-store/submitting/) — Página oficial da Apple com o processo de submissão e o que preparar. 🇺🇸
- [App Store Connect — Help](https://developer.apple.com/help/app-store-connect/) — Manual oficial do App Store Connect: builds, TestFlight, preços, metadados e lançamento. 🇺🇸
- [Apple Developer Program](https://developer.apple.com/programs/) — Como se inscrever no programa (anual, pago) necessário para publicar na App Store. 🇺🇸
- [TestFlight](https://developer.apple.com/testflight/) — Distribuição beta oficial da Apple para testers internos e externos. 🇺🇸
- [Flutter — Build and release an Android app](https://docs.flutter.dev/deployment/android) — Guia oficial do Flutter para gerar App Bundle assinado e publicar no Google Play. 🇺🇸
- [Flutter — Build and release an iOS app](https://docs.flutter.dev/deployment/ios) — Guia oficial do Flutter para arquivar no Xcode e publicar na App Store. 🇺🇸
- [Expo — Submit to app stores](https://docs.expo.dev/deploy/submit-to-app-stores/) — Como enviar builds para as lojas com EAS Submit. 🆕 🇺🇸
- [React Native — Publishing to Google Play Store](https://reactnative.dev/docs/signed-apk-android) — Guia oficial de assinatura e publicação de apps React Native no Android. 🇺🇸
- [React Native — Publishing to Apple App Store](https://reactnative.dev/docs/publishing-to-app-store) — Guia oficial de publicação de apps React Native na App Store. 🇺🇸
- [OWASP Mobile Application Security (MAS)](https://mas.owasp.org/) — Padrão e guia de testes de segurança para apps mobile, referência em auditorias. 🇺🇸

## 📚 Livros
- [Kotlin com Android (Casa do Código)](https://www.casadocodigo.com.br/products/livro-kotlin-android) — Livro em português para criar apps Android com Kotlin, da editora brasileira Casa do Código. 💰
- [Flutter (Casa do Código)](https://www.casadocodigo.com.br/products/livro-flutter) — Livro em português sobre Flutter e Dart para apps Android e iOS. 💰
- [React Native (Casa do Código)](https://www.casadocodigo.com.br/products/livro-react-native) — Livro em português sobre React Native, do ambiente à publicação. 💰
- [Kotlin em ação (Novatec)](https://novatec.com.br/livros/kotlin-em-acao/) — Tradução do clássico escrito por membros do time do Kotlin na JetBrains. 💰
- [Flutter na prática (Novatec)](https://novatec.com.br/livros/flutter-na-pratica/) — Tradução de Flutter in Action, com projetos completos. 💰
- [The Swift Programming Language (gratuito)](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/) — O livro oficial do Swift, online e gratuito, do tour da linguagem à referência gramatical. 🇺🇸
- [Hacking with iOS (gratuito online)](https://www.hackingwithswift.com/read) — Livro de Paul Hudson com projetos de iOS, lido gratuitamente no site. 🇺🇸
- [SwiftUI by Example (gratuito)](https://www.hackingwithswift.com/quick-start/swiftui) — Livro-referência gratuito com centenas de receitas curtas de SwiftUI. 🇺🇸
- [Kotlin in Action, Second Edition (Manning)](https://www.manning.com/books/kotlin-in-action-second-edition) — Segunda edição (2024) do livro definitivo de Kotlin, agora com coroutines e Flow. 🆕 💰 🇺🇸
- [Effective Kotlin (Kt. Academy)](https://kt.academy/book/effectivekotlin) — Boas práticas de Kotlin, item a item, de Marcin Moskała. 💰 🇺🇸
- [Kotlin Coroutines: Deep Dive (Kt. Academy)](https://kt.academy/book/coroutines) — O livro mais completo sobre coroutines e Flow, essenciais no Android moderno. 💰 🇺🇸
- [Flutter in Action (Manning)](https://www.manning.com/books/flutter-in-action) — Introdução completa a Flutter e Dart com um app construído ao longo do livro. 💰 🇺🇸
- [Flutter Apprentice (Kodeco)](https://www.kodeco.com/books/flutter-apprentice) — Livro da Kodeco para iniciantes em Flutter, com projetos guiados. 💰 🇺🇸
- [React Native in Action (Manning)](https://www.manning.com/books/react-native-in-action) — Livro de Nader Dabit sobre React Native, do básico a módulos nativos. 💰 🇺🇸
- [Big Mountain Studio — livros visuais de SwiftUI](https://www.bigmountainstudio.com/) — Livros de referência visual de SwiftUI (views, animações, dados), muito usados no mercado. 💰 🇺🇸

## 🎥 Canais no YouTube
### Em português
- [Flutterando](https://www.youtube.com/@Flutterando) — Canal da maior comunidade Flutter do Brasil: cursos, lives e arquitetura.
- [Rodrigo Rahman](https://www.youtube.com/@RodrigoRahman) — Flutter e Dart em profundidade, do criador da Academia do Flutter.
- [Deivid Willyan | Flutter](https://www.youtube.com/@FlutterCursos) — Cursos gratuitos de Flutter por nível e dicas de carreira.
- [Toshi Ossada](https://www.youtube.com/@Toshiossada) — Flutter, Dart e arquitetura de apps, com projetos ao vivo.
- [Alex Felipe](https://www.youtube.com/@AlexFelipeDev) — Android com Kotlin e Jetpack Compose explicados com calma para iniciantes.
- [Android — Simples e Direto](https://www.youtube.com/@androidsimplesedireto) — Cursos gratuitos de Android e Compose em português.
- [Douglas Motta](https://www.youtube.com/@DouglasMotta) — Android moderno, arquitetura, testes e carreira, por um engenheiro Android brasileiro.
- [Android Dev BR](https://www.youtube.com/@AndroidDevBr) — Palestras e lives da comunidade brasileira de Android.
- [Lucas Montano](https://www.youtube.com/@LucasMontano) — Kotlin, Android e carreira internacional em big techs, com opiniões diretas.
- [CodandoTV](https://www.youtube.com/@CodandoTV) — Kotlin Multiplatform e Compose Multiplatform em português, com cursos completos publicados em 2025. 🆕
- [CocoaHeads Brasil](https://www.youtube.com/@cocoaheadsbr) — Palestras dos meetups da comunidade brasileira de iOS/Swift.
- [Portal Hugo Cursos](https://www.youtube.com/@tutoriais01) — Cursos gratuitos e extensos de Swift, React Native e outras tecnologias.
- [Rocketseat](https://www.youtube.com/@rocketseat) — Eventos e aulas gratuitas de React Native e Expo, entre outras stacks.
- [Matheus Battisti — Hora de Codar](https://www.youtube.com/@MatheusBattisti) — Cursos gratuitos de React Native e JavaScript para iniciantes.
- [DevClub | Programação](https://www.youtube.com/@canaldevclub) — Aulas completas de React Native + Expo, incluindo o curso do zero de 2025. 🆕

### Em inglês
- [Android Developers (oficial)](https://www.youtube.com/@AndroidDevelopers) — Canal oficial do Google: Now in Android, Compose, novidades de cada versão. 🇺🇸
- [Kotlin by JetBrains (oficial)](https://www.youtube.com/@Kotlin) — Canal oficial do Kotlin: KotlinConf, KMP e tutoriais. 🇺🇸
- [Flutter (oficial)](https://www.youtube.com/@flutterdev) — Canal oficial do Flutter: Widget of the Week, novidades e codelabs. 🇺🇸
- [Apple Developer (oficial)](https://www.youtube.com/@AppleDeveloper) — Canal oficial da Apple com sessões da WWDC e tutoriais. 🇺🇸
- [Expo (oficial)](https://www.youtube.com/@ExpoDevelopers) — Canal oficial do Expo com tutoriais e lançamentos. 🇺🇸
- [Philipp Lackner](https://www.youtube.com/@PhilippLackner) — Um dos maiores canais de Android: Compose, arquitetura, KMP e boas práticas. 🇺🇸
- [Stevdza-San](https://www.youtube.com/@StevdzaSan) — Tutoriais de Android com Kotlin, Compose e KMP. 🇺🇸
- [Paul Hudson (Hacking with Swift)](https://www.youtube.com/@twostraws) — Swift e SwiftUI pelo autor do 100 Days of SwiftUI. 🇺🇸
- [Sean Allen](https://www.youtube.com/@seanallen) — Swift, SwiftUI e carreira iOS em vídeos objetivos. 🇺🇸
- [Swiftful Thinking](https://www.youtube.com/@SwiftfulThinking) — Playlists de SwiftUI do iniciante ao avançado, incluindo arquitetura. 🇺🇸
- [Reso Coder](https://www.youtube.com/@ResoCoder) — Flutter com arquitetura, testes e Bloc. 🇺🇸
- [Andrea Bizzotto (Code with Andrea)](https://www.youtube.com/@codewithandrea) — Flutter profissional: Riverpod, Firebase e apps de produção. 🇺🇸
- [notJust.dev](https://www.youtube.com/@notjustdev) — React Native e Expo com clones de apps reais, ao vivo. 🇺🇸
- [William Candillon](https://www.youtube.com/@wcandillon) — Animações e gestos avançados em React Native com Reanimated e Skia. 🇺🇸
- [Simon Grimm](https://www.youtube.com/@galaxies_dev) — React Native, Expo e Ionic com projetos completos. 🇺🇸

## 🎙️ Podcasts
- [Hipsters Ponto Tech](https://www.hipsters.tech/) — Podcast brasileiro de tecnologia da Alura, com episódios sobre Flutter, Android, iOS e carreira.
- [Universo Flutter](https://creators.spotify.com/pod/profile/universoflutter/) — Podcast em português dedicado a Flutter e ao mercado mobile.
- [Android Developers Backstage](https://adbackstage.libsyn.com/) — Podcast oficial do time de Android do Google. 🇺🇸
- [Talking Kotlin](https://talkingkotlin.com/) — Podcast da JetBrains com o time e a comunidade Kotlin. 🇺🇸
- [Fragmented](https://fragmentedpodcast.com/) — Podcast veterano sobre desenvolvimento Android e engenharia de software. 🇺🇸
- [Swift by Sundell — Podcast](https://www.swiftbysundell.com/podcast/) — Conversas com desenvolvedores iOS sobre Swift e arquitetura. 🇺🇸
- [It's All Widgets! — Flutter Podcast](https://itsallwidgets.com/podcast) — Entrevistas com desenvolvedores Flutter sobre apps reais. 🇺🇸
- [React Native Radio](https://infinite.red/react-native-radio) — Podcast da Infinite Red sobre o ecossistema React Native. 🇺🇸
- [Now in Android](https://developer.android.com/series/now-in-android) — Série oficial (vídeo, podcast e newsletter) com as novidades do Android a cada duas semanas. 🇺🇸

## 📰 Sites, blogs e newsletters
- [Kotlin Brasil](https://kotlin.dev.br/) — Site da comunidade brasileira de Kotlin com artigos, eventos e links das comunidades. 🆕
- [Alura — artigos de Mobile](https://www.alura.com.br/artigos/mobile) — Artigos em português sobre Android, iOS, Flutter e React Native.
- [TabNews](https://www.tabnews.com.br/) — Comunidade brasileira de conteúdo técnico; pesquise por Flutter, Android ou iOS.
- [Android Developers Blog](https://android-developers.googleblog.com/) — Blog oficial do Android com lançamentos, políticas do Play e novidades de ferramentas. 🇺🇸
- [Android Weekly](https://androidweekly.net/) — Newsletter semanal gratuita com os melhores artigos de Android e Kotlin. 🇺🇸
- [Kotlin Blog (JetBrains)](https://blog.jetbrains.com/kotlin/) — Blog oficial do Kotlin: releases, KMP e Compose Multiplatform. 🇺🇸
- [iOS Dev Weekly](https://iosdevweekly.com/) — Newsletter semanal de iOS mais tradicional, curada por Dave Verwer. 🇺🇸
- [Swift by Sundell](https://www.swiftbysundell.com/) — Artigos de Swift e SwiftUI por John Sundell. 🇺🇸
- [Hacking with Swift](https://www.hackingwithswift.com/) — Maior site de tutoriais gratuitos de Swift, SwiftUI e iOS. 🇺🇸
- [SwiftLee](https://swiftlee.com/) — Artigos semanais de Antoine van der Lee sobre Swift, Xcode e SwiftUI. 🇺🇸
- [Apple Developer — Videos (WWDC)](https://developer.apple.com/videos/) — Todas as sessões da WWDC, a principal fonte de novidades de iOS e Swift. 🇺🇸
- [Flutter — tag na DEV Community](https://dev.to/t/flutter) — Artigos da comunidade sobre Flutter, muitos em português.
- [React Native — Blog oficial](https://reactnative.dev/blog) — Anúncios de versões e da Nova Arquitetura. 🇺🇸
- [Expo Blog](https://expo.dev/blog) — Novidades do SDK, EAS e Expo Router. 🇺🇸
- [This Week in React](https://thisweekinreact.com/) — Newsletter semanal de React com seção dedicada a React Native. 🇺🇸
- [React Native Newsletter](https://reactnativenewsletter.com/) — Newsletter gratuita com o melhor do ecossistema React Native. 🇺🇸
- [State of Mobile 2025 (Sensor Tower)](https://sensortower.com/state-of-mobile-2025) — Relatório anual do mercado mobile: downloads, receita e tendências. 🆕 🇺🇸

## 🛠️ Ferramentas
### IDEs, emuladores e ambiente
- [Android Studio (PT-BR)](https://developer.android.com/studio?hl=pt-br) — IDE oficial do Android, com emulador, profiler, Compose Preview e Gemini integrado.
- [Xcode](https://developer.apple.com/xcode/) — IDE oficial da Apple para iOS, com simulador, previews de SwiftUI e assistente de código. 🇺🇸
- [Visual Studio Code](https://code.visualstudio.com/) — Editor mais usado para Flutter e React Native, com extensões oficiais. 🇺🇸
- [Install Flutter (oficial)](https://docs.flutter.dev/install) — Guia oficial de instalação do Flutter SDK em macOS, Windows e Linux. 🇺🇸
- [Expo Go](https://expo.dev/go) — App para rodar seu projeto React Native no celular sem compilar código nativo. 🇺🇸
- [Kotlin Playground](https://play.kotlinlang.org/) — Rode Kotlin no navegador sem instalar nada. 🇺🇸
- [Swift Playground](https://developer.apple.com/swift-playground/) — App gratuito da Apple para iPad e Mac que ensina Swift e permite criar apps completos. 🇺🇸
- [DartPad](https://dartpad.dev/) — Editor online oficial de Dart e Flutter. 🇺🇸
- [Expo Snack](https://snack.expo.dev/) — React Native no navegador, com preview no celular via Expo Go. 🇺🇸
- [Android Debug Bridge (adb)](https://developer.android.com/tools/adb) — Ferramenta de linha de comando para instalar apps, ver logs e controlar dispositivos. 🇺🇸
- [scrcpy](https://github.com/Genymobile/scrcpy) — Espelhe e controle um Android real no computador, gratuito e sem root. 🇺🇸
- [FVM — Flutter Version Management](https://fvm.app/) — Gerencie várias versões do Flutter por projeto. 🇺🇸
- [pub.dev](https://pub.dev/) — Repositório oficial de pacotes Dart e Flutter, com notas de qualidade. 🇺🇸

### Bibliotecas e backend
- [Hilt (injeção de dependência)](https://developer.android.com/training/dependency-injection/hilt-android) — Solução oficial de DI para Android, sobre o Dagger. 🇺🇸
- [Koin](https://insert-koin.io/) — Injeção de dependência pragmática em Kotlin, também para KMP. 🇺🇸
- [Ktor](https://ktor.io/) — Cliente HTTP (e servidor) em Kotlin da JetBrains, padrão em projetos KMP. 🇺🇸
- [SQLDelight](https://sqldelight.github.io/sqldelight/) — Gera código Kotlin tipado a partir de SQL; funciona em Android, iOS e KMP. 🇺🇸
- [SKIE](https://skie.touchlab.co/) — Melhora a interoperabilidade Kotlin → Swift em projetos KMP (enums, Flow, suspend). 🆕 🇺🇸
- [Riverpod](https://riverpod.dev/) — Gerenciamento de estado reativo para Flutter, evolução do Provider. 🇺🇸
- [Bloc](https://bloclibrary.dev/) — Padrão BLoC para Flutter: estado previsível e testável. 🇺🇸
- [Drift](https://drift.simonbinder.eu/) — Persistência reativa e tipada sobre SQLite para Flutter. 🇺🇸
- [React Navigation](https://reactnavigation.org/) — Biblioteca de navegação padrão do React Native. 🇺🇸
- [React Native Reanimated](https://docs.swmansion.com/react-native-reanimated/) — Animações e gestos rodando na thread de UI. 🇺🇸
- [Firebase](https://firebase.google.com/) — Backend gerenciado do Google: auth, banco, storage, push, analytics e crash reports. 🇺🇸
- [Supabase](https://supabase.com/) — Alternativa open source ao Firebase, com Postgres, auth e realtime; SDKs para Flutter, Swift, Kotlin e RN. 🇺🇸
- [RevenueCat](https://www.revenuecat.com/) — Assinaturas e compras no app para iOS, Android, Flutter e RN, sem lidar direto com as lojas. 🇺🇸

### Testes, depuração e monitoramento
- [Test your Compose layout](https://developer.android.com/develop/ui/compose/testing) — Guia oficial de testes de UI no Jetpack Compose. 🇺🇸
- [XCTest](https://developer.apple.com/documentation/xctest) — Framework oficial de testes unitários e de UI da Apple. 🇺🇸
- [Testing Flutter apps](https://docs.flutter.dev/testing/overview) — Guia oficial de testes unitários, de widget e de integração no Flutter. 🇺🇸
- [Maestro](https://docs.maestro.dev/) — Testes E2E de UI em YAML para Android, iOS, Flutter e React Native; o mais simples de adotar. 🆕 🇺🇸
- [Patrol](https://patrol.leancode.co/) — Testes E2E para Flutter com acesso a permissões, notificações e WebViews nativas. 🆕 🇺🇸
- [Detox](https://wix.github.io/Detox/) — Testes E2E gray-box para React Native. 🇺🇸
- [detekt](https://detekt.dev/) — Análise estática de código Kotlin. 🇺🇸
- [SwiftLint](https://github.com/realm/SwiftLint) — Linter de estilo e convenções para Swift. 🇺🇸
- [Proxyman](https://proxyman.com/) — Proxy HTTP para inspecionar o tráfego do app em iOS e Android. 🇺🇸
- [Firebase Crashlytics](https://firebase.google.com/products/crashlytics) — Relatórios de crash em tempo real, gratuito, para Android, iOS, Flutter e RN. 🇺🇸
- [Sentry for Mobile](https://sentry.io/solutions/mobile-developers/) — Monitoramento de erros e performance com SDKs para todas as stacks mobile. 🇺🇸

### Publicação, CI/CD e design
- [fastlane](https://fastlane.tools/) — Automatiza screenshots, assinatura, builds e envio para as lojas. 🇺🇸
- [Codemagic](https://codemagic.io/start/) — CI/CD feito para mobile (Flutter, RN, nativo), com plano gratuito. 🇺🇸
- [GitHub Actions (documentação em PT-BR)](https://docs.github.com/pt/actions) — CI gratuito para projetos públicos; runners macOS para builds de iOS.
- [Xcode Cloud](https://developer.apple.com/xcode-cloud/) — CI/CD da Apple integrado ao Xcode e ao TestFlight, com horas gratuitas. 🇺🇸
- [Expo Application Services (EAS)](https://expo.dev/services) — Build, submit e updates OTA na nuvem para apps React Native. 🇺🇸
- [Shorebird](https://shorebird.dev/) — Code push (atualizações sem passar pela loja) para Flutter. 🆕 🇺🇸
- [Figma](https://www.figma.com/) — Ferramenta padrão de design de interfaces; use com os kits oficiais da Apple e do Material. 🇺🇸
- [SF Symbols](https://developer.apple.com/sf-symbols/) — Biblioteca oficial de milhares de ícones da Apple, integrada ao SwiftUI. 🇺🇸
- [FlutterFlow](https://flutterflow.io/) — Construtor visual (low-code) que exporta código Flutter. 💰 🇺🇸

## 🧪 Projetos práticos e desafios
- [Now in Android (app oficial)](https://github.com/android/nowinandroid) — App completo do Google que demonstra a arquitetura recomendada com Compose, Hilt e Room. 🇺🇸
- [Jetpack Compose samples (oficial)](https://github.com/android/compose-samples) — Amostras oficiais de Compose (Jetnews, Jetchat, Jetsnack) para estudar UI. 🇺🇸
- [Pokedex Compose (skydoves)](https://github.com/skydoves/pokedex-compose) — Projeto de referência de Android moderno: Compose, Hilt, Retrofit e Room. 🆕 🇺🇸
- [KMP production sample (Kotlin)](https://github.com/kotlin/kmp-production-sample) — App real de RSS em Kotlin Multiplatform mantido pela JetBrains. 🇺🇸
- [Kotlin Multiplatform samples (oficial)](https://kotlinlang.org/docs/multiplatform/multiplatform-samples.html) — Lista oficial de exemplos KMP por caso de uso. 🆕 🇺🇸
- [Food Truck (Apple, WWDC22)](https://github.com/apple/sample-food-truck) — App de exemplo da Apple em SwiftUI para iPhone, iPad e Mac. 🇺🇸
- [Flutter samples (oficial)](https://github.com/flutter/samples) — Coleção oficial de exemplos e demos do Flutter. 🇺🇸
- [Flutter UI Challenges](https://github.com/lohanidamodar/flutter_ui_challenges) — Mais de 100 telas de UI recriadas em Flutter para estudar layout. 🇺🇸
- [Desafios (Flutterando)](https://github.com/Flutterando/desafios) — Desafios de código propostos pela comunidade Flutterando, em português.
- [Expo examples (oficial)](https://github.com/expo/examples) — Projetos de exemplo oficiais do Expo para cada recurso do SDK. 🇺🇸
- [react-native-template-obytes](https://github.com/obytes/react-native-template-obytes) — Template de produção para React Native com Expo, TypeScript e boas práticas. 🆕 🇺🇸
- [App Ideas Collection](https://github.com/florinpop17/app-ideas) — Ideias de apps por nível de dificuldade para construir seu portfólio. 🇺🇸
- [awesome-flutter](https://github.com/Solido/awesome-flutter) — Lista curada de pacotes, artigos e apps open source em Flutter. 🇺🇸
- [awesome-ios](https://github.com/vsouza/awesome-ios) — Lista curada do ecossistema iOS, mantida por um brasileiro. 🇺🇸
- [awesome-react-native](https://github.com/jondot/awesome-react-native) — Lista curada de componentes, ferramentas e apps de React Native. 🇺🇸
- [kmp-awesome](https://github.com/terrakok/kmp-awesome) — Lista curada de bibliotecas e ferramentas Kotlin Multiplatform. 🆕 🇺🇸
- [Open-source iOS apps](https://github.com/dkhamsing/open-source-ios-apps) — Lista colaborativa de apps iOS open source para ler código de produção. 🇺🇸
- [Open-source Flutter apps (open-apps)](https://github.com/tortuvshin/open-apps) — Diretório de apps Flutter reais e open source. 🇺🇸
- [Empresas que usam Flutter no Brasil](https://github.com/FlutterComunidadeBR/empresas-que-usam-flutter-no-brasil) — Repositório colaborativo listando empresas e apps brasileiros feitos em Flutter.

## 🤖 IA na prática
Em mobile, a IA entrou **dentro das IDEs oficiais**: o Android Studio vem com o Gemini (chat, modo agente e testes em linguagem natural) e o Xcode 26 tem assistente integrado com ChatGPT, Claude e outros modelos. Ao mesmo tempo, os aparelhos passaram a rodar modelos **no próprio dispositivo** (Gemini Nano no Android, Foundation Models no iOS 26), o que abre uma categoria nova de funcionalidades para o seu app. Use as duas coisas — com critério.

**Para aprender**
- Cole o erro de build do Gradle ou do Xcode inteiro (não só a última linha) e peça: *"explique a causa provável e o passo mínimo para corrigir"*. Erros de build são a principal barreira de quem começa.
- Peça para **converter** um layout XML para Jetpack Compose, uma tela UIKit para SwiftUI ou um componente de classe do React para função com hooks — e depois peça para explicar cada mudança.
- Peça um exercício por conceito: *"me dê 3 exercícios sobre `LazyColumn` (ou `List` no SwiftUI, `ListView.builder` no Flutter, `FlatList` no RN) com gabarito"*.
- Peça para explicar o ciclo de vida (Activity/Composable, View no SwiftUI, StatefulWidget) desenhando o fluxo em texto, e confirme na documentação oficial.
- Use o preview: no Compose e no SwiftUI, peça o código, cole e veja a tela sem emulador. Se o preview quebra, a IA errou.

**Para trabalhar**
- No Android Studio, use o [Gemini](https://developer.android.com/studio/gemini/overview): o **Agent Mode** faz mudanças em vários arquivos e o **Journeys** escreve testes de ponta a ponta em linguagem natural. No Xcode, use o [assistente integrado](https://developer.apple.com/documentation/xcode/writing-code-with-intelligence-in-xcode). Em Flutter e React Native, [Cursor](https://cursor.com/), [Copilot](https://github.com/features/copilot) ou [Claude Code](https://code.claude.com/docs/en/overview) no VS Code.
- Conecte o agente ao seu projeto com MCP: o Flutter tem o [servidor MCP do Dart](https://docs.flutter.dev/ai/get-started) e o Expo tem o [Expo MCP](https://docs.expo.dev/mcp/). Isso reduz APIs inventadas.
- Bons usos: gerar `data class`/`struct`/model a partir de um JSON, escrever testes de unidade e de widget, criar strings de acessibilidade, traduzir arquivos de localização, escrever o texto da listagem na loja e revisar o código antes do PR.
- Depois de **cada** sugestão aceita: compile, rode os testes, rode o linter (detekt, SwiftLint, `flutter analyze`, ESLint) e teste **em um aparelho real**. Emulador não pega problema de permissão, câmera, GPS nem bateria.

**IA dentro do app (on-device e na nuvem)**
- Comece pelo que já vem pronto: [ML Kit](https://developers.google.com/ml-kit?hl=pt-br) (OCR, códigos de barras, rostos, tradução) roda em Android e iOS sem treinar nada.
- Modelos de linguagem no aparelho: [Gemini Nano](https://developer.android.com/ai/gemini-nano) no Android e o [Foundation Models framework](https://developer.apple.com/documentation/foundationmodels) no iOS 26 — sem custo por chamada, funcionam offline e os dados não saem do celular.
- Para modelos próprios: [LiteRT](https://ai.google.dev/edge/litert), [Core ML](https://developer.apple.com/documentation/coreml/), [ExecuTorch](https://docs.pytorch.org/executorch/stable/index.html) ou [MLC LLM](https://github.com/mlc-ai/mlc-llm).
- Para chamar Gemini/Claude/GPT na nuvem, **nunca coloque a chave da API no app** (ela é extraída em minutos): use o [Firebase AI Logic](https://firebase.google.com/docs/ai-logic), o [Vercel AI SDK](https://ai-sdk.dev/docs/getting-started/expo) com um backend seu, ou um proxy próprio.

**Limites e boas práticas**
- IA **inventa APIs**, principalmente de versões recentes (Compose, SwiftUI, Expo SDK mudam rápido). Confirme na documentação oficial e nas notas de versão.
- Ela tende a ignorar ciclo de vida, permissões, estados de erro e acessibilidade. Revise cada um desses pontos você mesmo.
- Google Play e App Store têm políticas para conteúdo gerado por IA e para privacidade; leia as [diretrizes de revisão](https://developer.apple.com/app-store/review/guidelines/) e a [ajuda do Play Console](https://support.google.com/googleplay/android-developer/?hl=pt-BR) antes de lançar.
- Dados de usuário não vão para prompts sem consentimento e sem política da empresa. Prefira on-device quando o dado for sensível.
- Entenda o que você aceita: em entrevista e em produção, o código é seu.

### Assistentes e ferramentas de IA para desenvolver
- [Gemini in Android Studio (oficial)](https://developer.android.com/studio/gemini/overview) — Assistente de IA integrado ao Android Studio: chat, geração de código, análise de crashes e preview. 🆕 🇺🇸
- [Agent Mode — Android Studio](https://developer.android.com/studio/gemini/agent-mode) — Modo agente do Gemini que executa tarefas de várias etapas e edita vários arquivos. 🆕 🇺🇸
- [Journeys — Android Studio](https://developer.android.com/studio/gemini/journeys) — Testes de ponta a ponta descritos em linguagem natural e executados pelo Gemini no emulador. 🆕 🇺🇸
- [Writing code with intelligence in Xcode (oficial)](https://developer.apple.com/documentation/xcode/writing-code-with-intelligence-in-xcode) — Documentação da Apple sobre o assistente do Xcode 26 (ChatGPT, Claude e outros modelos). 🆕 🇺🇸
- [JetBrains AI Assistant](https://www.jetbrains.com/ai/) — IA no IntelliJ/Android Studio (via plugin) e no Fleet, com suporte a Kotlin e KMP. 🆕 🇺🇸
- [GitHub Copilot](https://github.com/features/copilot) — Autocomplete e chat no VS Code, Xcode e Android Studio; gratuito para estudantes. 🆕 🇺🇸
- [Cursor](https://cursor.com/) — Editor baseado no VS Code com IA integrada; bom para Flutter e React Native. 🆕 🇺🇸
- [Claude Code](https://code.claude.com/docs/en/overview) — Agente de código no terminal: refatora, escreve testes e navega projetos nativos e multiplataforma. 🆕 🇺🇸
- [Get started developing with AI (Flutter)](https://docs.flutter.dev/ai/get-started) — Guia oficial do Flutter para usar assistentes de IA com regras de contexto e servidor MCP do Dart. 🆕 🇺🇸
- [Using MCP with Expo](https://docs.expo.dev/mcp/) — Servidor MCP oficial do Expo para conectar agentes de IA à documentação e ao projeto. 🆕 🇺🇸
- [Firebase Studio](https://firebase.studio/) — Ambiente na nuvem do Google que prototipa apps (incluindo Flutter) a partir de prompts. 🆕 🇺🇸

### IA on-device e SDKs para o seu app
- [AI on Android (oficial)](https://developer.android.com/ai) — Hub oficial de IA no Android: Gemini Nano, ML Kit, LiteRT e Firebase AI Logic. 🆕 🇺🇸
- [Gemini Nano (Android)](https://developer.android.com/ai/gemini-nano) — Modelo do Google que roda no próprio aparelho, com APIs para resumo, reescrita e descrição de imagens. 🆕 🇺🇸
- [ML Kit (PT-BR)](https://developers.google.com/ml-kit?hl=pt-br) — APIs prontas de visão e texto (OCR, códigos de barras, tradução, rostos) para Android e iOS. 🆕
- [LiteRT (antigo TensorFlow Lite)](https://ai.google.dev/edge/litert) — Runtime do Google para executar modelos no dispositivo em Android, iOS e embarcados. 🆕 🇺🇸
- [Google AI Edge Gallery](https://github.com/google-ai-edge/gallery) — App open source que roda modelos Gemma e outros LLMs 100% no aparelho; ótimo para estudar. 🆕 🇺🇸
- [Firebase AI Logic](https://firebase.google.com/docs/ai-logic) — Use a API Gemini a partir do app sem expor sua chave, com SDKs para Android, iOS, Flutter e RN. 🆕 🇺🇸
- [Foundation Models framework (Apple)](https://developer.apple.com/documentation/foundationmodels) — Framework do iOS 26 para usar o modelo on-device da Apple Intelligence com Swift, com saída estruturada. 🆕 🇺🇸
- [Meet the Foundation Models framework (WWDC25)](https://developer.apple.com/videos/play/wwdc2025/286/) — Sessão oficial da WWDC25 apresentando o framework. 🆕 🇺🇸
- [Core ML](https://developer.apple.com/documentation/coreml/) — Framework da Apple para rodar modelos de machine learning no dispositivo. 🇺🇸
- [Flutter AI Toolkit](https://docs.flutter.dev/ai/ai-toolkit) — Widgets de chat e integração com Gemini e Vertex AI para apps Flutter. 🆕 🇺🇸
- [Vercel AI SDK — Expo](https://ai-sdk.dev/docs/getting-started/expo) — Guia oficial para usar o AI SDK (streaming, tools) em apps React Native com Expo. 🆕 🇺🇸
- [react-native-ai (Callstack)](https://github.com/callstackincubator/ai) — Execução de LLMs on-device em React Native, compatível com o Vercel AI SDK. 🆕 🇺🇸
- [ExecuTorch (PyTorch)](https://docs.pytorch.org/executorch/stable/index.html) — Runtime do PyTorch para modelos on-device em Android e iOS. 🆕 🇺🇸
- [MLC LLM](https://github.com/mlc-ai/mlc-llm) — Motor universal para rodar LLMs localmente, com SDKs Android e iOS. 🆕 🇺🇸

## 📜 Certificações
Em mobile, **certificação pesa menos que portfólio**: recrutadores olham apps publicados, código no GitHub e domínio da stack. O Google **encerrou** a Associate Android Developer; a única certificação ligada à Apple é a App Development with Swift (Certiport), voltada a estudantes; Flutter e React Native não têm certificação oficial. O que existe de útil: o certificado **gratuito** do Google Play sobre listagem na loja, os certificados profissionais da Meta no Coursera e os certificados de formação de plataformas brasileiras, que ajudam no currículo.
- [App Development with Swift (Apple/Certiport)](https://certiport.pearsonvue.com/Certifications/Apple/App-Dev-With-Swift/Overview.aspx) — Única certificação oficial ligada à Apple, aplicada pela Certiport: níveis Associate e Certified User. 💰 🇺🇸
- [Desenvolvimento de apps com Swift — certificação (Apple Brasil)](https://www.apple.com/br/education/higher-education/app-development/) — Página oficial da Apple em português explicando o programa de ensino e a certificação em Desenvolvimento de Apps com Swift.
- [Google Play Store Listing Certificate (gratuito)](https://playacademy.withgoogle.com/certificate/) — Certificado gratuito do Google sobre listagem e políticas da Play Store; exame online de até 5 horas. 🇺🇸
- [Google Developers Certification (página oficial)](https://developers.google.com/certification) — Página oficial: hoje lista apenas o Store Listing Certificate e as certificações do Google Cloud — a Associate Android Developer foi encerrada. 🇺🇸
- [Meta Android Developer Professional Certificate (Coursera)](https://www.coursera.org/professional-certificates/meta-android-developer) — Certificado profissional da Meta em Kotlin/Android, reconhecido em currículos. 💰 🇺🇸
- [Meta iOS Developer Professional Certificate (Coursera)](https://www.coursera.org/professional-certificates/meta-ios-developer) — Certificado profissional da Meta em Swift/iOS. 💰 🇺🇸
- [Formações de Mobile da Alura (certificado)](https://www.alura.com.br/cursos-online-mobile) — Certificados de formação da Alura em Android, iOS, Flutter e React Native, reconhecidos por empresas brasileiras. 💰
- [Introdução ao Flutter (DIO) — com certificado](https://www.dio.me/courses/introducao-ao-flutter) — Curso gratuito que emite certificado de conclusão.
- [Curso de Flutter COMPLETO (Cursa) — com certificado](https://cursa.com.br/curso-de-flutter-completo/513) — Certificado digital gratuito ao concluir o curso da Flutterando.

## 💼 Carreira e vagas
Vagas de mobile no Brasil se concentram em bancos e fintechs (Nubank, Itaú, PicPay, Inter), varejo, saúde e consultorias, com forte presença de Kotlin, Swift, Flutter e React Native. Os títulos mais comuns são *Desenvolvedor(a) Android*, *iOS*, *Mobile* (multiplataforma) e, cada vez mais, *KMP*. Os salários variam bastante por senioridade e cidade — use as fontes abaixo como referência, não como regra. Dica: nos repositórios de vagas do GitHub, pesquise por "Flutter", "Kotlin" ou "Swift" nas issues abertas.
- [Guia Salarial 2026 (Robert Half)](https://www.roberthalf.com/br/pt/insights/guia-salarial) — Pesquisa salarial anual com faixas para desenvolvedores mobile no Brasil por senioridade. 🆕
- [Desenvolvedor Mobile — Salário Brasil (salario.com.br)](https://www.salario.com.br/profissao/desenvolvedor-mobile-cbo-317110/) — Média salarial oficial (CAGED) por porte de empresa, estado e nível.
- [Stack Overflow Developer Survey 2025](https://survey.stackoverflow.co/2025/) — Pesquisa global com salários e uso de Kotlin, Swift, Dart, Flutter e React Native. 🆕 🇺🇸
- [Programathor — vagas Mobile](https://programathor.com.br/jobs-mobile) — Vagas de tecnologia no Brasil filtradas por mobile.
- [Programathor — vagas Flutter](https://programathor.com.br/jobs-flutter) — Vagas de Flutter no Brasil.
- [Programathor — vagas React Native](https://programathor.com.br/jobs-react-native) — Vagas de React Native no Brasil.
- [androiddevbr/vagas](https://github.com/androiddevbr/vagas) — Mural de vagas Android da comunidade brasileira, como issues no GitHub.
- [CocoaHeadsBrasil/vagas](https://github.com/CocoaHeadsBrasil/vagas) — Vagas de iOS e macOS publicadas pela comunidade brasileira.
- [flutterbr/vagas](https://github.com/flutterbr/vagas) — Vagas de Flutter e Dart no GitHub.
- [react-brasil/vagas](https://github.com/react-brasil/vagas) — Vagas de React e React Native no GitHub.
- [Flutterando — Vagas e oportunidades](https://github.com/Flutterando/forum/discussions/categories/vagas-e-oportunidades) — Categoria de vagas nas discussões da comunidade Flutterando.
- [Github Vagas Brasil](https://githubvagasbrasil.vercel.app/) — Agregador que reúne as vagas dos repositórios brasileiros (Android, iOS, Flutter, React) em um só lugar.
- [GeekHunter](https://www.geekhunter.com/pt) — Plataforma brasileira onde empresas fazem propostas a devs.
- [Coodesh](https://coodesh.com/) — Vagas tech no Brasil com processos seletivos padronizados.
- [Remotar](https://remotar.com.br/) — Vagas 100% remotas para brasileiros.
- [Tech Interview Handbook](https://www.techinterviewhandbook.org/) — Preparação completa para entrevistas técnicas. 🇺🇸
- [Android Interview Questions](https://github.com/amitshekhariitbhu/android-interview-questions) — Perguntas frequentes de entrevistas Android, por tema. 🇺🇸
- [iOS Interview Questions](https://github.com/onthecodepath/iOS-Interview-Questions) — Perguntas de entrevista de iOS com respostas. 🇺🇸

## 👥 Comunidades
- [Flutterando (Discord)](https://discord.com/invite/flutterando-509072164666867753) — Maior comunidade Flutter do Brasil, com milhares de membros e canais por tema.
- [Flutter Brasil (Discord)](https://discord.com/invite/XCsGvD6sw7) — Comunidade brasileira de Flutter para dúvidas, carreira e troca de experiências.
- [Flutterando — fórum no GitHub](https://github.com/Flutterando/forum) — Discussões, vagas e arquitetura organizadas em GitHub Discussions.
- [Flutter Brasil (Telegram)](https://t.me/flutterbrasil) — Grupo brasileiro de Flutter no Telegram.
- [Android Dev BR (Telegram)](https://t.me/androiddevbr) — Maior comunidade brasileira de Android; também tem GitHub e canal no YouTube.
- [Kotlin Brasil (Telegram)](https://t.me/kotlinbr) — Grupo brasileiro de Kotlin, Android e KMP.
- [Comunidade Kotlin Brasil — Telegram, Discord e eventos](https://kotlin.dev.br/comunidade/) — Página que centraliza todos os grupos e eventos da comunidade Kotlin no Brasil. 🆕
- [Swift BR (Telegram)](https://t.me/swiftbr) — Grupo brasileiro de Swift e iOS no Telegram.
- [CocoaHeads Brasil (GitHub)](https://github.com/CocoaHeadsBrasil) — Comunidade brasileira de iOS/macOS com meetups em várias cidades e mural de vagas.
- [Google Developer Groups (PT-BR)](https://developers.google.com/community?hl=pt-br) — GDGs e eventos do Google no Brasil (DevFest, I/O Extended), com muita pauta de Android e Flutter.
- [He4rt Developers](https://heartdevs.com/) — Comunidade brasileira open source com Discord ativo e canais de mobile.
- [Desenvolvedores Brasil (Discord)](https://discord.com/invite/t3vYGUuK6P) — Comunidade brasileira com dicas, cursos, mentorias e vagas.
- [Lista de grupos de tecnologia no Telegram (TI-Brasil)](https://github.com/TI-Brasil/lista-telegram-brasil) — Diretório de grupos brasileiros no Telegram, incluindo Android, iOS e Flutter.
- [Flutter Community (oficial)](https://flutter.dev/community) — Página oficial com Discord, fóruns e grupos de Flutter no mundo. 🇺🇸
- [Kotlin Community (oficial)](https://kotlinlang.org/community/) — Slack oficial do Kotlin (canais #android, #multiplatform), fóruns e KUGs. 🇺🇸
- [Swift Forums (oficial)](https://forums.swift.org/) — Fórum oficial da linguagem Swift, onde a evolução da linguagem é discutida. 🇺🇸
- [Apple Developer Forums](https://developer.apple.com/forums/) — Fórum oficial da Apple com respostas de engenheiros da empresa. 🇺🇸
- [Expo Developers (Discord)](https://discord.com/invite/expo) — Discord oficial do Expo e React Native. 🇺🇸
- [r/androiddev](https://www.reddit.com/r/androiddev/) — Subreddit de desenvolvimento Android. 🇺🇸
- [r/iOSProgramming](https://www.reddit.com/r/iOSProgramming/) — Subreddit de desenvolvimento iOS. 🇺🇸
- [r/FlutterDev](https://www.reddit.com/r/FlutterDev/) — Subreddit de Flutter. 🇺🇸
- [r/reactnative](https://www.reddit.com/r/reactnative/) — Subreddit de React Native. 🇺🇸

## 🚨 Como contribuir
Achou um link quebrado, um curso novo ou uma ferramenta que merece estar aqui? Abra uma issue usando os templates do repositório ou envie um pull request. Critérios: link funcionando, conteúdo legal e gratuito ou claramente marcado como pago, com uma linha de descrição. Detalhes em [CONTRIBUTING.md](./CONTRIBUTING.md).

## 📄 Licença
Este projeto está sob a licença [MIT](./LICENSE). Feito com 💙 por [Arthur Coutinho (@arthurspk)](https://github.com/arthurspk) e pela comunidade do [Guia Dev Brasil](https://github.com/arthurspk/guiadevbrasil).

## 💙 Apoie o projeto
Dê uma ⭐ neste repositório e no [guia principal](https://github.com/arthurspk/guiadevbrasil), compartilhe com quem está começando e siga o projeto nas redes:

[<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">](https://github.com/arthurspk)
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">](https://www.linkedin.com/in/arthurspk/)
[<img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X (Twitter)">](https://x.com/manotoquinho)
[<img src="https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">](https://www.instagram.com/arthurspk/)
[<img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook">](https://www.facebook.com/seixasqlc/)
