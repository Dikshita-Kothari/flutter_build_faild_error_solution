# flutter_build_faild_error_solution

- andoid/app/build.gradle
``` 
  ndkVersion = "28.0.13004108"

    compileOptions {
        sourceCompatibility = JavaVersion.VERSION_17
        targetCompatibility = JavaVersion.VERSION_17
    }

    kotlinOptions {
        jvmTarget = JavaVersion.VERSION_17.toString()
    }
```

- android/gradle.properties
```
org.gradle.java.home=C\:\\Program Files\\Java\\jdk-17
```
