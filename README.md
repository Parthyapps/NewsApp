## News App Using Kotlin

## Project Structure
### Packages:
 - di (Dependency Injection)
 - network (Retrofit services)
 - repository (Data handling)
 - ui (Activities, Fragments, ViewModels)
 - database (Room Entities and DAOs)
 - utils (Helper classes)

## Dependency Injection (Dagger)
   - Add dependencies to build.gradle:
```groovy
    implementation 'com.google.dagger:dagger:2.x'
    kapt 'com.google.dagger:dagger-compiler:2.x'
```