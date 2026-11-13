# Baby Vigía

Academic team project at UNLaM, with active participation by **Federico Pucci**.

**Android · Java · MQTT · Eclipse Paho · ESP32 / Wokwi · Sensors**

Monitoring and control prototype connecting sound/movement sensors with an Android client. The Android sources subscribe to MQTT status topics, send control commands and integrate the phone gyroscope. The hardware directory contains the supplied Arduino sketch and Wokwi diagram.

## Contents and scope

- `android/`: the two Android activity source files retained from the coursework.
- `hardware/`: sketch, Wokwi diagram, library list and original simulation link.

The local archive does not contain a complete Android Gradle project or the UI layout resources referenced by the activities. These sources are published as coursework material; a standalone Android build is not claimed.

For the hardware prototype, load the sketch and diagram in Wokwi and install the libraries listed in `hardware/libraries.txt`. MQTT broker/topic configuration is in the sources; use your own isolated configuration when running a demonstration.

No hardware execution or broker interaction was performed during publication.
