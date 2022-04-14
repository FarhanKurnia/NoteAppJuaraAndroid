# NoteAppJuaraAndroid

This Note Mobile Apps was built using Kotlin for First Season Juara Android Submission 2022 </br>

## Feature:
- Create Note
- Read Note
- Update Note
- Delete All Note
- Set Priority Note 


------------------------------------------------------------------------
## Implementations
1. Clone Repository </br>
    ```
    git clone https://github.com/FarhanKurnia/NoteAppJuaraAndroid.git
    ```

2. Set up Dependency </br>
   - (Add build.gradle/project)
    ```
    ext {
    roomVersion = '2.2.1'
    archLifecycleVersion = '2.2.0-rc02'
    androidxArchVersion = '2.1.0'
    coreTestingVersion = "2.1.0"
    coroutines = '1.3.2'
    materialVersion = "1.0.0"
    }
    ```
    
    - (Add build.gradle/module)
    ```
    plugins {
    id 'kotlin-kapt'
    id 'kotlin-android-extensions'
    }
    
   dependencies {
    // Room
    implementation "androidx.room:room-runtime:$rootProject.roomVersion"
    implementation "androidx.room:room-ktx:$rootProject.roomVersion"
    kapt "androidx.room:room-compiler:$rootProject.roomVersion"
    androidTestImplementation "androidx.room:room-testing:$rootProject.roomVersion"

    // Lifecycle
    implementation "androidx.lifecycle:lifecycle-extensions:$rootProject.archLifecycleVersion"
    kapt "androidx.lifecycle:lifecycle-compiler:$rootProject.archLifecycleVersion"
    androidTestImplementation "androidx.arch.core:core-testing:$rootProject.androidxArchVersion"

    // ViewModel
    implementation "androidx.lifecycle:lifecycle-viewmodel-ktx:$rootProject.archLifecycleVersion"

    // Coroutines
    api "org.jetbrains.kotlinx:kotlinx-coroutines-android:$rootProject.coroutines"

    // UI
    implementation "com.google.android.material:material:$rootProject.materialVersion"

    // Testing
    androidTestImplementation "androidx.arch.core:core-testing:$rootProject.coreTestingVersion"
    }
    ```

3. Run Debug App </br>


------------------------------------------------------------------------
## Main Material
- [Kotlin Basic](https://developer.android.com/courses/android-basics-kotlin/unit-1?authuser=2)
  - [Create your first app](https://developer.android.com/courses/pathways/android-basics-kotlin-two)
  - [Build Basic Layout](https://developer.android.com/courses/pathways/android-basics-kotlin-three)
  - [Add a button to an app](https://developer.android.com/courses/pathways/android-basics-kotlin-four)
  
- [Layouts](https://developer.android.com/courses/android-basics-kotlin/unit-2?authuser=2)
  - [Get user input in an app: Part 1](https://developer.android.com/courses/pathways/android-basics-kotlin-unit-2-pathway-1?authuser=2)
  - [Get user input in an app: Part 2](https://developer.android.com/courses/pathways/android-basics-kotlin-unit-2-pathway-2?authuser=2)
 
- [Navigations](https://developer.android.com/courses/android-basics-kotlin/unit-3?authuser=2)
  - [Navigate between screens](https://developer.android.com/courses/pathways/android-basics-kotlin-unit-3-pathway-1?authuser=2)
  - [Introduction to the Navigation component](https://developer.android.com/courses/pathways/android-basics-kotlin-unit-3-pathway-2?authuser=2)
  - [Architecture components](https://developer.android.com/courses/pathways/android-basics-kotlin-unit-3-pathway-3?authuser=2)
  - [Advanced navigation app examples](https://developer.android.com/courses/pathways/android-basics-kotlin-unit-3-pathway-4?authuser=2)

- [Data Persistence](https://developer.android.com/courses/android-basics-kotlin/unit-5?authuser=2)
  - [Introduction to SQL, Room, and Flow](https://developer.android.com/courses/pathways/android-basics-kotlin-unit-5-pathway-1?authuser=2)
  - [Save changes in your app](https://developer.android.com/courses/pathways/android-basics-kotlin-unit-5-pathway-2?authuser=2)

------------------------------------------------------------------------
