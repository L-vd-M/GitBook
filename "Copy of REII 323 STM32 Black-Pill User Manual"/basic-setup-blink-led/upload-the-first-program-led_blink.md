---
description: >-
  In this section the steps will be provided needed to upload the first program
  to the STM32F411(Black-Pill) development board.
---

# ▶ Upload the first Program: LED\_BLINK

1.  First, debug the program by selecting the following icon -> ![](../.gitbook/assets/Debug.png). The window shown below will open after the debug option was selected. No changes will be made to the settings. Select "**Apply**" and "**Ok**".

    <figure><img src="../.gitbook/assets/Debug Main.png" alt=""><figcaption></figcaption></figure>
2.  The following window shown below will open after "OK" was selected. The LED on the ST-LINK V2 will flash rapidly when entering the debug window.

    <figure><img src="../.gitbook/assets/Debug Window.png" alt=""><figcaption></figcaption></figure>
3. In this window, there are some new icons:
   * Terminate and Relaunch --> ![](<../.gitbook/assets/1. Debug Page Icons\_Terminate and Relaunch.png>)
   * Resume --> ![](<../.gitbook/assets/1. Debug Page Icons\_Resume.png>)
   * Suspend --> ![](<../.gitbook/assets/2. Debug Page Icons\_Suspend.png>)
   * Terminate --> ![](<../.gitbook/assets/1. Debug Page Icons\_Terminate.png>)

{% tabs %}
{% tab title="Terminate and Relaunch" %}
![](<../.gitbook/assets/1. Debug Page Icons\_Terminate and Relaunch.png>) --> The "**Terminate and Relaunch**" button will close the debugging window and return to the coding window for a brief moment after which it will open the debugging window again.
{% endtab %}

{% tab title="Resume" %}
![](<../.gitbook/assets/1. Debug Page Icons\_Resume.png>) --> The "**Resume**" window will start the program on the STM32F411.
{% endtab %}

{% tab title="Suspend" %}
![](<../.gitbook/assets/2. Debug Page Icons\_Suspend.png>) --> The "**Suspend**" button will stop the program on the STM32F411 in its current state.
{% endtab %}

{% tab title="Terminate" %}
![](<../.gitbook/assets/1. Debug Page Icons\_Terminate.png>) --> The "**Terminate**" button will resume the program on the STM32F411, close the debugging window and return to the coding environment.
{% endtab %}
{% endtabs %}
