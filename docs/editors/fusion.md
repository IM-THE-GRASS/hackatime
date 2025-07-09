# Fusion Setup Guide

![Fusion](/images/editor-icons/fusion-128.png)

Follow these steps to start tracking your activity in Fusion with Hackatime.

## Step 1: Log into Hackatime

Make sure you have a [Hackatime account](https://hackatime.hackclub.com) and are logged in.

## Step 2: Run the Setup Script

Visit the [setup page](https://hackatime.hackclub.com/my/wakatime_setup) to automatically configure your API key and endpoint. This ensures everything works perfectly with Hackatime.

## Step 3: Install the Fusion Plugin

### Prerequisites
- Fusion 360
- Python
- Windows 10/11


#### 1. Download the Add-in
-   Go to the [github page for this plugin](https://github.com/LiveWaffle/Hackatime-Fusion360).
-   Click the green `<> Code` button, then click **Download ZIP**. (or you can use git if you have it)
-   Unzip the downloaded file. You will get a folder named something like `Hackatime-Fusion360-main`.

<div align="center">
<img width="429" src="https://hc-cdn.hel1.your-objectstorage.com/s/v3/52d8e378b207d2445dbc01edaa4f6ed8813a3c05_image.png" />
<br>
<img src="https://hc-cdn.hel1.your-objectstorage.com/s/v3/70965a04be2979c78067961f9f427d7ba5e337bf_image.png" />
</div>

#### 2. Add to Fusion 
-   Open Fusion.
-   Go to the **UTILITIES** tab and click the **Scripts and Add-Ins** icon.
<div align="center"><img width="600" src="https://hc-cdn.hel1.your-objectstorage.com/s/v3/3547fca54c8c1537bbde115acb1abcaae28e98d1_8eede38a-9a08-4618-9fb3-20b0fc1543e9.png" /></div>

-   In the new window, select the **Add-Ins** tab.
<div align="center"><img src="https://hc-cdn.hel1.your-objectstorage.com/s/v3/58d97f9690b998680ce37ba686eb2e67974a27ef_29a37634-eb1c-4bf2-b728-bc83e3078db6.png" /></div>

-   Click the green **+** icon next to "My Add-Ins".
<div align="center"><img src="https://hc-cdn.hel1.your-objectstorage.com/s/v3/58d97f9690b998680ce37ba686eb2e67974a27ef_29a37634-eb1c-4bf2-b728-bc83e3078db6.png" /></div>

-   In the file dialog, navigate to and select `Hackatime-Fusion360-main/Hackatime-Fusion360-main` folder.
<div align="center"><img src="https://hc-cdn.hel1.your-objectstorage.com/s/v3/71afae29e9d63d85820ab85742d25cbf1c0411c8_image.png" /></div>

#### 4. Run the Add-in
-   The `FusionWakaTime` add-in should now appear in your list.
-   Select it and click **Run**.
-   **IMPORTANT:** Check the **Run on startup** box so it runs automatically every time you open Fusion 360.


Once configured, your activity time will automatically appear on your [Hackatime dashboard](https://hackatime.hackclub.com). Happy collaborating!