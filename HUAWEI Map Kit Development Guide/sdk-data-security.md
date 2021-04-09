# SDK Data Security<a name="EN-US_TOPIC_0000001098683758"></a>

-   [How Does the SDK Work?](#section124962819524)
-   [What Permissions Are Required for Using the SDK?](#section15489113619524)
-   [What Data Does the SDK Collect?](#section18210529528)
-   [How Does the SDK Protect Your Data?](#section59571517533)

## How Does the SDK Work?<a name="section124962819524"></a>

The HMS Core Map SDK is integrated into your app during app packaging. It starts when the app is launched and stops as soon as the app is closed, without performing additional operations in the background.

## What Permissions Are Required for Using the SDK?<a name="section15489113619524"></a>

Map Kit has integrated the required permissions. Therefore, you do not need to apply for these permissions. Other permissions are not required.

-   android.permission.**ACCESS\_NETWORK\_STATE**: Checks whether the current network is available.
-   android.permission.**ACCESS\_WIFI\_STATE**: Obtains the current Wi-Fi connection status and the information about WLAN hotspots.

## What Data Does the SDK Collect?<a name="section18210529528"></a>

The SDK uses the app ID, package name, and API call status of the app for the continuous improvement of Map Kit.

It does not collect personal data of users.

## How Does the SDK Protect Your Data?<a name="section59571517533"></a>

It does not collect personal data of users.

