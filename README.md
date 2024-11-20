# Raspberry Pi & Accelerometer with WEGnology's EEA

This is a repository that contains companion code to [this EEA How To guide](https://docs.app.wnology.io/guides/how-to-use-wegnologys-embedded-edge-agent-to-calculate-FFT-values/).

![WEGnology Dashboard showing FFT data](https://docs.app.wnology.io/images/guides/how-to-use-wegnologys-embedded-edge-agent-to-calculate-FFT-values/step-7-chart-with-messy-frequency.png)

Each folder is named according to a step in the guide and contains completed code for the guide.

**Step 2** is a simple example that simply ensures that the accelerometer is connected correctly and the Raspberry Pi is set up correctly.

**Step 3** introduces the [WEGnology EEA](https://docs.app.wnology.io/edge-compute/embedded-edge-agent/overview) without any [registered functions](https://docs.app.wnology.io/workflows/data/registered-function/) to make sure that your device can connect to the WEGnology Platform.

**Step 4** introduces a simple registered function that reads the accelerometer once every 10 seconds and sends the X-axis value back to the cloud.

**Step 6** changes the registered function for reading the accelerometer from 1 value to reading 1024 readings, measuring sample rate, and reporting both values to the cloud.

## To Use

1. Clone this repository to your Raspberry Pi.
1. Follow Step 1 in the How To guide to set up your Raspberry Pi.
1. Create an [Embedded Device](https://docs.app.wnology.io/devices/embedded/) and [Access Key](https://docs.app.wnology.io/applications/access-keys/) in your WEGnology Application.
1. Each step folder has a readme which includes instructions on how to run the main.py file.

For any questions, please visit the [WEGnology Forums](https://forums.app.wnology.io/).
