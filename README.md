<h1 align="center">MovieComposeLaboratory(experimental)</h1>

[![GitHub license](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/Nanamare/)

### About
The application is a simple movie searching app using Jetpack Compose. Purpose is to **acquire enough knowledge** that can be used in the company. 
<br><br>

### Architecture
 - Base on [Google Recommended Architecture](https://developer.android.com/jetpack/guide#recommended-app-arch) (UI Layer - Domain Layer - Data Layer) similar to Clean Architecture
 - Using Mvvm with repository pattern (Model-View-ViewModel)

<img width="302" alt="스크린샷 2021-12-23 오후 10 55 10" src="https://user-images.githubusercontent.com/17498974/147250233-2f022a65-3cc2-4546-89d9-0d9037b2db59.png"> [ImageLink](https://github.com/rmoustafa/Kotlin-Coroutines-Clean-Architecture)
<br><br>

### 🛠 Built With 🛠
- Kotlin (Coroutine, Flow)
- Compose
  - Navigation
  - ViewModel(AAC)
  - Paging3
- Dagger-Hilt
- Retrofit
- OkHttp
- Kotlinx-serialization
- Accompanist
 - SwipeRefresh
 - System-ui-controller
 <br><br>
 
 ### Modularization
  - App (UI Layer)
  - Data (Data Layer)
  - Domain (Domain Layer)
  - base (Collection of utility functions used in UI Layer)
  - buildSrc (Managing dependencies)
<img width="310" alt="스크린샷 2021-12-23 오후 8 19 59" src="https://user-images.githubusercontent.com/17498974/147242594-74726b66-8471-486c-b3ce-caef7f60bbf1.png">
<br><br>

 ### ScreenShot
 <p align="center">
<img src="https://user-images.githubusercontent.com/17498974/147248400-df98cefe-a3b9-4c73-92f1-ca31e7af1064.jpeg" width="31%"  />
<img src="https://user-images.githubusercontent.com/17498974/147248379-a5b410bd-822d-418d-8b79-2d1e35ed6762.jpeg"  width="31%" />
<img src="https://user-images.githubusercontent.com/17498974/147248396-aa4220d0-30d1-4351-8788-39b0e661c08f.jpeg" width="31%" />
</p>
<br>

 ### Open API
  - [TheMovieDB API](https://api.themoviedb.org)
<br>

 ### TODO
- [ ] MovieDetailScreen
- [ ] Theme (Current support System using Dark Theme)
- [ ] Animation
