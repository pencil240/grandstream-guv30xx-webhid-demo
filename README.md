# WebHID Demo for Grandstream GUV30xx devices

A demo that connects to a Grandstream GUV30xx headset

[WebHID API specification](https://wicg.github.io/webhid/index.html)


## Browser requirements

WebHID is available in Chrome 78+ behind a flag. To use WebHID, navigate to chrome://flags in a browser window and enable "Experimental Web Platform Features", then restart Chrome.

## Usage

* Plug the headset into a USB port.
* Open the [demo page](https://pencil240.github.io/grandstream-guv30xx-webhid-demo/)
* Click connect
* In the device chooser dialog, select the headset
* Check that a "Connected to device" message is displayed.

After connecting to the headset, try clicking the "Answer" button to send an output report. This will cause LEDs to light up on the headset and control unit. The headset should respond with HID input reports. You can also press buttons on the control unit/headset to cause the headset to send HID input reports.
