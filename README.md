# TESS Payments Android SDK

<p align="center">
  <a href="https://tesspayments.com">
      <img src="/media/Tess-payments-12.png" alt="TESS Payments" width="400px"/>
  </a>
</p>

TESS Payments Android SDK was developed and designed with one purpose: to help the Android developers easily integrate the TESS Payments API Payment Platform for a specific merchant. 

The main aspects of the TESS Payments Android SDK:

- [Kotlin](https://developer.android.com/kotlin) is the main language
- [Retrofit](http://square.github.io/retrofit/) is the API machine 
- [KDoc](https://kotlinlang.org/docs/reference/kotlin-doc.html) code coverage
- API debug [logging](https://github.com/square/okhttp/tree/master/okhttp-logging-interceptor)
- Minimum SDK 16+
- Sample Application

To properly set up the SDK, read [Wiki](https://github.com/TESSPayments/tesspayments-android-sdk/wiki) first.
To get used to the SDK, download a [sample app](https://github.com/TESSPayments/tesspayments-android-sdk/tree/main/sample).

## Setup

Add to the root build.gradle:

```groovy
allprojects {
    repositories {
        ...
        jcenter()
        maven { url 'https://jitpack.io' }
    }
}
```

Add to the package build.gradle:

```groovy
dependencies {
    implementation 'com.github.akurateco:akurateco-android-sdk:{latest-version}'
}
```

<!-- Latest version is: ![](https://jitpack.io/v/akurateco/akurateco-android-sdk.svg) -->

Also, it is possible to download the latest artifact from the [releases page](https://github.com/TESSPayments/tesspayments-android-sdk/releases).

## Sample

| Sale | Recurring Sale | Capture |
|-|-|-|
| ![](/media/sale.gif) | ![](/media/recurring-sale.gif) | ![](/media/capture.gif) |

| Creditvoid | Get Trans Status | Get Trans Details |
|-|-|-|
| ![](/media/creditvoid.gif) | ![](/media/get-trans-status.gif) | ![](/media/get-trans-details.gif) |

## Getting help

To report a specific issue or feature request, open a [new issue](https://github.com/TESSPayments/tesspayments-ios-sdk/issues/new).

Or write a direct letter to the [support@tesspayments.com](mailto:support@tesspayments.com).

## License

MIT License. See the [LICENSE](https://github.com/TESSPayments/tesspayments-ios-sdk/blob/main/LICENSE) file for more details.

## Contacts

<!-- ![](/media/footer.jpg) -->

Website: https://tesspayments.com  
Phone: [+974-4402-0138](tel:97444020138)  
Email: [support@tesspayments.com](mailto:support@tesspayments.com)  
Address: 27th Floor, UDC Tower 1, The Pearl Qatar  

© 2016 - 2022 TESS Payments. All rights reserved.
