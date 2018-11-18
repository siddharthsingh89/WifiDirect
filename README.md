# Wi-Fi Direct sample

Shows how to use the Wi-Fi Direct API to discover devices and connect to the them over Wi-Fi Direct.

- **Advertise a Wi-Fi Direct device:**
A device can advertise its presence so that other Wi-Fi Direct devices
can discover and connect to it. There are optional settings that
an advertiser may specify, such as custom information elements
to share during discovery, and options for how to establish a connection.
An advertiser can also specify advanced optional settings such as
pairing configuration methods (in order of preference)
and the preferred pairing procedure.
The advertiser can also be cofigured in legacy mode wherein legacy
(non-WiFiDirect) clients can connect to it.
The legacy mode also supports specifying a SSID and a passphrase.
- **Discover a Wi-Fi Direct device:** Discover advertising devices over Wi-Fi Direct.
- **Connect to a device/Accept an incoming connection:** After discovering a Wi-Fi Direct device, a device may connect to it. The advertising device may accept or decline the connection.
The connector can also be configured with optional advanced settings
such as the pairing configuration methods (in order of preference)
and the preferred pairing procedure.
- **Send data over Wi-Fi Direct after connecting to a device:** Connected peers may open TCP and UDP sockets and send data. This sample just sends text strings as a sample.

