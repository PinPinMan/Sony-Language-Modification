# Sony-Language-Modification

This is my journey of unlocking my japan `Sony Cyber-shot DSC-HX30V` camera.
Language
![Image](https://github.com/user-attachments/assets/48205ab3-8494-428d-ab33-71c64c2b1686)

---

# Instructions

### Hardware

-   Press the Menu button & Scroll down to the Menu Page
    -   ![Image](https://github.com/user-attachments/assets/554c1232-ab94-4bda-baf6-a541d83f7333)
-   Change to `USB Connect Settings` to `Mass Storage`
    -   ![Image](https://github.com/user-attachments/assets/07e50eca-a90a-475f-899c-325a2ba94ea7)
-   Connect the camera to your computer
    > [!Warning]
    > If you encounter issues connecting with your PC, where the camera shows connecting, but the computer doesn't detect new connected device at all
    > ![Image](https://github.com/user-attachments/assets/0bbaea00-c571-485d-a7cd-c2a04a33c6a4)
    > The cause can be the Micro USB is not a data cable and only charges power.
    > or you can use this [reddit post](https://www.reddit.com/r/sony/comments/l0bw55/camera_stuck_on_connecting_when_using_imaging/) to debug.

### Software

-   Check Device Competability [here](https://openmemories.readthedocs.io/devices.html)
-   Install [Zadig](https://zadig.akeo.ie/) as the sony program needs libusb drivers
-   After installing Zadig, Run it and `List All Devices` under `Options`
    -   ![Image](https://github.com/user-attachments/assets/77c91262-ee6d-445c-a6b0-94d811ff4636)
-   Select Sony Device
    -   ![Image](https://github.com/user-attachments/assets/67a8f08e-ab4b-4b48-9187-d930963576f8)
-   Make sure its the correct camera connected, change to `libusb-win32(v1.2.7.3)` and click Install
    -   ![Image](https://github.com/user-attachments/assets/dbc029bd-f228-43b9-a17f-59b63def3585)
-   Next, Open pmca-gui-v0.18-14. Go to Tweaks and Click Start tweaking (service mode)
    -   **First**, Click on Unlock protected settings Protection Disabled
    -   ![Image](https://github.com/user-attachments/assets/7712680a-2693-45a7-aafe-b859dfe07cf7)
        > [!WARNING]
        > There may be a bug where it will disconnect your camera when you Start tweaking
        > Go back to Zadig and install the driver again. if you do not find your device, it could be named `Sony HD Camera`
        > Next, Try again

---

> [!Important]
> Sony-PMCA-RE newest version `v0.18` doesn't have `Start tweaking (service mode)`
> Theres a post about a previous version with the mode on [ma1co/Sony-PMCA-RE Issue Comment](https://github.com/ma1co/Sony-PMCA-RE/issues/308#issuecomment-1284330632)

---

# Youtube References

-   https://www.youtube.com/watch?v=nTbQDAUTOXY&t
-   https://www.youtube.com/watch?v=Udunk6HG1uk
-   https://www.youtube.com/watch?v=JyrqRoNos6E&t
-   https://youtu.be/Udunk6HG1uk?=SLM4y-RJCnA46yCu
-   https://youtu.be/JyrqRoNos6E?=e9uTDVoctiTnZRfC
