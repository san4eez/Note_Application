# Приложение Заметки с Календарем
Данное приложение разработано на базе kotlin 1.4.31 с версией gradle 4.2.0. В приложении присутствуют 2 экрана. Первый экран отображает главную страницу приложения, где располагается календарь и сами заметки; Второй экран включает себя возможность добавлять и редактировать заметки. 
# Использованные Библиотеки
- implementation "androidx.appcompat:appcompat:$rootProject.appCompatVersion"
- implementation "androidx.activity:activity-ktx:$rootProject.activityVersion"
- implementation "androidx.room:room-ktx:$rootProject.roomVersion"
- kapt "androidx.room:room-compiler:$rootProject.roomVersion"
- androidTestImplementation "androidx.room:room-testing:$rootProject.roomVersion"
- implementation "androidx.lifecycle:lifecycle-viewmodel-ktx:$rootProject.lifecycleVersion"
- implementation "androidx.lifecycle:lifecycle-livedata-ktx:$rootProject.lifecycleVersion"
- implementation "androidx.lifecycle:lifecycle-common-java8:$rootProject.lifecycleVersion"
- implementation "org.jetbrains.kotlin:kotlin-stdlib-jdk7:$kotlin_version"
- api "org.jetbrains.kotlinx:kotlinx-coroutines-core:$rootProject.coroutines"
- api "org.jetbrains.kotlinx:kotlinx-coroutines-android:$rootProject.coroutines"
- implementation "androidx.constraintlayout:constraintlayout:$rootProject.constraintLayoutVersion"
- implementation "com.google.android.material:material:$rootProject.materialVersion"
- testImplementation "junit:junit:$rootProject.junitVersion"
- androidTestImplementation "androidx.arch.core:core-testing:$rootProject.coreTestingVersion"
- androidTestImplementation ("androidx.test.espresso:espresso-core:$rootProject.espressoVersion", {exclude group: 'com.android.support', module: 'support-annotations'})
- androidTestImplementation "androidx.test.ext:junit:$rootProject.androidxJunitVersion"

![1](https://user-images.githubusercontent.com/80901672/189980614-6f9fa3d0-3de8-4af7-b915-5c242ee71064.jpg)
![2](https://user-images.githubusercontent.com/80901672/189980621-f623cd81-0356-4efd-a2f8-27b163c694fd.jpg)
