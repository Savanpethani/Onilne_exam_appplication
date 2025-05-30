<!-- PROJECT BADGES -->


<h1 align="center">🎓 Online Exam Application</h1>
<p align="center">
  Cross-platform Kotlin app (Android & iOS) for creating, scheduling, delivering and grading exams in real time.
</p>

<p align="center">
  <img src="docs/demo.gif" alt="App Demo" width="600"/>
</p>

---

## 📑 Table of Contents
1. [Features](#-features)
2. [Installation & Setup](#-installation--setup)
3. [Usage](#-usage)
4. [Testing](#-testing)
5. [Contributing](#-contributing)
6. [License](#-license)
7. [Contact](#-contact)

---

## ✨ Features
- 🔄 **Cross-Platform (MVVM)**  
  Kotlin Multiplatform for Android & iOS with Jetpack ViewModel & LiveData
- ⚡ **Real-Time Exam Flow**  
  Firebase Realtime Database & Cloud Functions for scheduling, delivery & auto-grading
- 🔐 **Secure REST API**  
  End-to-end encrypted endpoints (Retrofit + Spring Boot)
- 📊 **Analytics & Reporting**  
  Dynamic dashboards tracking completion rates & grading accuracy
- 🚀 **CI/CD Automation**  
  AWS CodePipeline & CodeBuild slashing deployment time by 20%

---

## 💾 Installation & Setup

### Prerequisites
- Android Studio (latest version)
- Firebase account
- Backend server (for API)

### Steps:
1. Clone the repository:
  - git clone https://github.com/Savanpethani/Onilne_exam_appplication.git
  - cd Onilne_exam_appplication
   
2. **Firebase Setup**:

- Create a Firebase project at [firebase.google.com](https://firebase.google.com/)

- Add Android and iOS apps to your Firebase project

- Download the `google-services.json` file and place it in `app/` directory

- Download the `GoogleService-Info.plist` file and place it in `iosApp/` directory (or the iOS module)

3. **API Configuration**:

- Open the file `AppConfig.kt` (located in `commonMain/kotlin/config/`)

- Set your backend API base URL:

```kotlin

const val BASE_URL = "https://your.backend.server/api/"

```

4. **Run the app**:

- Open the project in Android Studio

- Sync Gradle dependencies

- Run the app on an Android emulator or device

- For iOS, open the iOS module in Xcode and run

  

***🚀 Usage***

**Register & Login**
1. Sign up using email or OAuth (Google/Facebook)

2. Existing users can log in with credentials

**Create an Exam**
1. Tap "New Exam"

2. Configure:Question bank, Time limits and Grading schema

3. Share generated exam code with students

**Join & Take Exam**
1. Students enter exam code

2. Complete questions within time limit

3. Submit answers for auto-grading

**Live Grading & Analytics**
1. Real-time answer monitoring

2. Score override options

3. Performance report export (CSV format)

***🧪 Testing***

- ✅ Unit Tests: JUnit + Mockito (85% coverage)

- 📱 UI Tests:

- Espresso (Android)

- Kaspresso (Multiplatform)

- 🌐 Cloud Testing: Firebase Test Lab (Automated device matrix)



**📫 Contact**

**👤 Savan Kumar Pethani**

✉️ Email: savanpethani5@gmail.com

🌐 Portfolio: https://savankumar-pethani.netlify.app

💼 GitHub: Savanpethani
