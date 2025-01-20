# **App Demo**
![Home Screen](https://github.com/ShivanshKumar760/JobIt/blob/master/imagesHub/Home.jpeg)




# **JobIT**

**JobIT** is a cross-platform mobile application designed to simplify the job search process. It allows users to search for and apply to jobs through an intuitive and seamless interface. The app is built with **React Native** for compatibility across Android and iOS devices and utilizes modern development tools and APIs to enhance the user experience.

---

## **Features**
- **Job Search and Apply**: Users can search for jobs based on filters and detailed criteria.
- **Cross-Platform Compatibility**: Works seamlessly on both Android and iOS devices.
- **API Integration**: Utilizes the **JSearch API** from RapidAPI for job data and search functionalities.
- **Streamlined Development**: Built and tested using **Expo**, ensuring fast iteration cycles.
- **App Publishing**: Production-ready builds created using **EAS (Expo Application Services)** for deployment on the **Google Play Store** and **Apple App Store**.
- **Modern UI**: Designed for a responsive and engaging user experience.

---

## **Tech Stack**
- **React Native**: For building the mobile application.
- **Expo**: For development, testing, and building.
- **EAS (Expo Application Services)**: For creating production-ready APK and IPA files.
- **JSearch API (RapidAPI)**: For fetching job-related data and providing search filters.

---

## **Setup Instructions**

### **1. Prerequisites**
- Install **Node.js** and **npm/yarn**.
- Install the **Expo CLI**:
  ```bash
  npm install -g expo-cli
  ```
- RapidAPI key for **JSearch API**.

### **2. Clone the Repository**
```bash
git clone https://github.com/ShivanshKumar760/JobIt.git
cd JobIt
```

### **3. Install Dependencies**
```bash
yarn install
# or
npm install
```

### **4. Configure Environment Variables**
Create an `.env` file in the root directory with the following:
```env
RAPIDAPI_KEY=your_rapidapi_key
```

### **5. Run the Application**
Start the development server:
```bash
expo start
```
- Scan the QR code using the Expo Go app on your mobile device (available on Google Play Store and Apple App Store).

---

## **Deployment Instructions**
### **1. EAS Build**
- Install EAS CLI:
  ```bash
  npm install -g eas-cli
  ```
- Authenticate with your Expo account:
  ```bash
  eas login
  ```
- Build the app:
  ```bash
  eas build
  ```
- Choose the platform (Android/iOS) and follow the instructions.

---

## **Live Project**
- **Expo Go Live Project**: Accessible via the Expo Console or Click Here to Scan QR code using Expo Go [QrCode](https://expo.dev/preview/update?message=jobtit-app&updateRuntimeVersion=1.0.0&createdAt=2025-01-17T07%3A43%3A52.362Z&slug=exp&projectId=29bb0ac3-959e-4096-8409-73835994707e&group=a93b9694-3f75-4716-b47c-beba87c706fd).
- **GitHub Repository**: [JobIT Code](https://github.com/ShivanshKumar760/JobIt.git)

---

## **Key Highlights**
- **API Integration**: Powered by the JSearch API for detailed job listings and filters.
- **Cross-Platform Compatibility**: Built for both Android and iOS devices.
- **Streamlined Deployment**: Published to app stores using Expo Application Services (EAS).

---

## **License**
This project is licensed under the MIT License.

---
