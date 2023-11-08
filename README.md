# PeerConnectivity

Reference:
https://www.ralfebert.com/ios-app-development/multipeer-connectivity/ 

The serviceType identifies the service (it must be a unique string, at most 15 characters long and can contain only ASCII lowercase letters, numbers and hyphens)

- The MCPeerID will uniquely identify the device; the displayName will be visible to other devices.
- The MCNearbyServiceAdvertiser advertises the service.
- The MCNearbyServiceBrowser looks for the service on the network.
- The MCSession manages all the connected devices (peers) and allows sending and receiving messages.

Info.plist must have the Bonjour services key with the following two values (the service type name needs to match!)
