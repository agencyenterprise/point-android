# PointSDK [![Maven Central](https://img.shields.io/maven-central/v/co.areyouonpoint.pointsdk/pointsdk)](https://repo1.maven.org/maven2/co/areyouonpoint/pointsdk/pointsdk/)

Access comprehensive health and fitness user data collected from across multiple wearable devices.

## Overview

Point SDK provides an easy, “plug-and-play” way for you to get access to the full-range of user health metrics powered by Point.

With Point SDK, you can:

- Access user health and fitness data collected through Fitbit and Oura and have it processed by Point.
- Decide the granularity of health and fitness data you would like to use from the wearable devices, depending on your app needs.
- Retrieve digested health metrics in a normalized, consistent data format across all devices

Point SDK provides a high-level interface for you to setup Fitbit and Oura on your app, which will be watching for new wearables data coming and proceed to process this data asynchronously in our backend.

Point is continually deriving new health metrics, health score updates, personalized health insights, and workout recommendations based on the wearables data, and you can retrieve those through our SDK at any time to deliver a custom experience to your users.


## Installation

```kotlin

repositories {
  mavenCentral()
}

dependencies {
  implementation 'co.areyouonpoint.pointsdk:pointsdk:1.0.2'
}
```

## About Point

Refer to [Official Page](https://www.areyouonpoint.co/)
