---
description: In this part, the basic pin configuration will be setup in the ".ioc" file.
---

# ⚙ Setting up the STM32F411 (Black-Pill)

The first window that will be shown if the project was created successfully in the previous section is the window shown below.

<figure><img src="../.gitbook/assets/Newly_Created Project_IOC.png" alt=""><figcaption></figcaption></figure>

## Pinout & Configuration

1.  The first thing to set up is the "**System Core**". It is located under "**Pinout & Configuration-> System Core**"

    <figure><img src="../.gitbook/assets/1. System Core.png" alt=""><figcaption></figcaption></figure>

    *   Next, the method of debugging has to be set. This is done by going to  "**Pinout & Configuration-> System Core->SYS**", and selecting "**Serial Wire**" in the "**Debug Drop Down list**" next to **Debug**.

        <figure><img src="../.gitbook/assets/1.1. System Core_sys.png" alt=""><figcaption></figcaption></figure>
2.  Next, the pin for the built-in LED can be set as an output. The pin for the built-in LED is "**PC13**". &#x20;

    <figure><img src="../.gitbook/assets/1. System Core.png" alt=""><figcaption></figcaption></figure>

    *   When searching for specific pins it is useful to make use of the pin finder. It is located at the bottom of the page as indicated below.

        <figure><img src="../.gitbook/assets/2.1 Pin Finder.png" alt=""><figcaption></figcaption></figure>
    *   Type the pin identifier into the search box. Whilst typing the name, a list of possible options will appear. Select the pin that is required as shown below. After the name of the pin has been selected, it will start to flash on the figure.&#x20;

        <figure><img src="../.gitbook/assets/2.2 Pin Located.png" alt=""><figcaption></figcaption></figure>
    *   Select the flashing pin through "**Left-Click**". Next, select the "**GPIO\_Output**" option.

        <figure><img src="../.gitbook/assets/2.3 Select Pin.png" alt=""><figcaption></figcaption></figure>
    *   Finally, rename the pin to make it easier to identify the pin later. This is done by selecting that same pin using "**Right-Click**" and selecting "**Enter User Label**". Enter a name eg "**Onboard\_LED**" which will replace the "**GPIO\_Output**" label shown in the figure below.

        <figure><img src="../.gitbook/assets/2.4 Change Pin Lable.png" alt=""><figcaption></figcaption></figure>

## Clock Configurations

1.  Shown below are the default "**Clock Configuration**" settings. For this project, no changes will be made to the default configuration.

    <figure><img src="../.gitbook/assets/2. Clock Configuration.png" alt=""><figcaption></figcaption></figure>

## Project Manager

1.  Shown below are the default "**Project Manager->Project**" settings.

    <figure><img src="../.gitbook/assets/3. Project Manager.png" alt=""><figcaption></figcaption></figure>

## Save project

From the figure below it can be seen that there is an "**\***" in front of the filename marked with the yellow box. This indicates that there were changes made to the file that still needs to be saved. Regularly save work to mitigate the chance of losing data and changes made to the program. This can easily be done by pressing "**ctrl + s**" at the same time.

<figure><img src="../.gitbook/assets/4.2. Save.png" alt=""><figcaption></figcaption></figure>

## Project Explorer

The "Project Explorer" window as shown below can be found at the left of the STM32CubeIDE window. In it, all of the files related to the project can be viewed.

<div align="left">

<figure><img src="../.gitbook/assets/5. Project Explorer.png" alt="" width="300"><figcaption></figcaption></figure>

</div>

The first file to look at is the "**main.c**", and inside this file, the function that will toggle the state of the LED will be written. This will be handled in the [led\_blink-code.md](led\_blink-code.md "mention") section.
