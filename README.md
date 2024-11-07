# ProductOrder

ProductOrder, **TeknoGenç Eğitim Projesi** kapsamında geliştirilmiş bir Flutter projesidir. Bu proje; kullanıcıların giriş yapabileceği, üyelik oluşturabileceği, ürün siparişi verebileceği, sepet işlemlerini yönetip ödeme yapabileceği kapsamlı özellikler sunar. Firebase ve diğer modern Flutter teknolojileri ile desteklenmiştir.

---

## Proje Özellikleri

Bu proje, bir mobil uygulamanın temel kullanıcı işlemlerinden ürün seçimi ve ödeme süreçlerine kadar geniş bir işlevsellik sunmaktadır.

### Kullanıcı Özellikleri
- **Giriş Yapma** ve **Üye Olma**: Firebase Authentication kullanılarak güvenli giriş yapılır, hızlı kayıt desteği sağlar.
- **Ürün İnceleme ve Sipariş Verme**: Mağazadaki ürünleri inceleyip sepete ekleyerek sipariş oluşturulabilir.
- **Sepet Yönetimi**: Seçilen ürünler sepete eklenir ve kullanıcı sipariş öncesi sepeti düzenleyebilir.
- **Ödeme İşlemi**: Firebase altyapısıyla uyumlu güvenli ödeme sistemi kullanılır.

---

## Kullanılan Teknolojiler

### Flutter
Proje, **Flutter** kullanılarak yazılmıştır. Flutter'ın sağladığı geniş UI bileşenleri kullanıcı dostu bir deneyim sunmaktadır.

### Firebase
Projenin backend işlemleri Firebase altyapısı ile sağlanmaktadır.
- **Firebase Authentication**: Güvenli kullanıcı kimlik doğrulaması sağlar.
- **Firebase Database**: Hızlı veri depolama ve yönetim işlemleri.
- **Firebase Cloud Functions** (opsiyonel): Ödeme gibi bazı görevlerde kullanılabilir.

### Diğer Kütüphaneler
- **Google Fonts**: Modern yazı tipleri ile arayüze estetik katılmıştır.
- **Provider**: Durum yönetimi için kullanılmıştır.
- **URL Launcher**: Dış bağlantılar için uygulama içinde tarayıcı açmayı sağlar.

---

## Kurulum ve Kullanım

Bu projeyi cihazınızda çalıştırmak için aşağıdaki adımları izleyin:

1. **Bağımlılıkları Yükleyin**: Aşağıdaki komutu çalıştırarak tüm Flutter bağımlılıklarını yükleyin.
   bash
   flutter pub get

2. **Firebase Yapılandırması: Firebase hesabınıza giriş yaparak projeyi oluşturun ve google-services.json dosyasını android/app klasörüne ekleyin. Firebase API anahtarınızı lib/service/auth.dart dosyasındaki ilgili alana yapıştırın.

3. **Projeyi Çalıştırın:

  bash
  flutter run

---

## Ekran Görüntüleri // Screenshots


![](https://github.com/mehmetgorer/TeknoGencFlutterProjesi/blob/main/FlutterProjectScreenShots/1.JPG)
![](https://github.com/mehmetgorer/TeknoGencFlutterProjesi/blob/main/FlutterProjectScreenShots/2.JPG)
![](https://github.com/mehmetgorer/TeknoGencFlutterProjesi/blob/main/FlutterProjectScreenShots/3.JPG)
![](https://github.com/mehmetgorer/TeknoGencFlutterProjesi/blob/main/FlutterProjectScreenShots/4.JPG)
![](https://github.com/mehmetgorer/TeknoGencFlutterProjesi/blob/main/FlutterProjectScreenShots/5.JPG)
![](https://github.com/mehmetgorer/TeknoGencFlutterProjesi/blob/main/FlutterProjectScreenShots/6.JPG)
![](https://github.com/mehmetgorer/TeknoGencFlutterProjesi/blob/main/FlutterProjectScreenShots/7.JPG)
![](https://github.com/mehmetgorer/TeknoGencFlutterProjesi/blob/main/FlutterProjectScreenShots/8.JPG)
![](https://github.com/mehmetgorer/TeknoGencFlutterProjesi/blob/main/FlutterProjectScreenShots/firebase.JPG)






# ProductOrder

ProductOrder is a **TeknoGenç Education Project** developed as a comprehensive Flutter application. This project allows users to log in, create an account, order products, manage a shopping cart, and complete payments. It integrates Firebase and various modern Flutter technologies for a seamless user experience.

---

## Project Features

This application provides a wide range of functionalities, from basic user actions in a mobile app to product selection and payment processes.

### User Features
- **Login and Sign-Up**: Secure login through Firebase Authentication, with quick and easy registration support.
- **Product Browsing and Ordering**: Users can browse store products, add them to the cart, and place orders.
- **Cart Management**: Products selected by the user are added to the cart, where they can review and adjust items before checkout.
- **Payment Processing**: A secure payment system integrated with Firebase for safe transactions.

---

## Technologies Used

### Flutter
The project is built using **Flutter**, leveraging its extensive UI components to create a user-friendly experience.

### Firebase
Backend operations are handled using Firebase infrastructure.
- **Firebase Authentication**: Ensures secure user authentication.
- **Firebase Database**: Allows quick data storage and management.
- **Firebase Cloud Functions** (optional): Useful for certain tasks, such as handling payments.

### Additional Libraries
- **Google Fonts**: Enhances the UI with modern typography.
- **Provider**: Used for state management.
- **URL Launcher**: Enables in-app browser access for external links.

---

## Installation and Usage

Follow these steps to run this project on your device:

1. **Install Dependencies**: Run the following command to install all Flutter dependencies.
   bash
   flutter pub get
2. ** Firebase Setup: Log into your Firebase account, create a new project, and add the google-services.json file to the android/app folder. Paste your Firebase API key into the designated area in lib/service/auth.dart.

3.**Run the Project:
bash
flutter run 
