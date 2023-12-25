# AMP-Term

Cisco AMP for Endpoints is an intelligent, enterprise-class advanced malware analysis and protection solution, with a telemetry model that uses big data, continuous analysis, and advanced analytics to detect, track, analyze, control, and block advanced malware outbreaks across all endpoints: PCs, Macs, mobile devices, and virtual systems.

The historical perspective gives you visibility into the following:

1. File Trajectory: Shows you the hosts where files were seen

2. Device Trajectory: Shows you the actions that files performed on a given host

Cisco AMP for Endpoints consists of the following elements:

1. Cisco Collective Security Intelligence Cloud: This is where the various detection and analytics engines reside.

  - Spero is a machine-learning malware detection engine that resides in the cloud. Spero relies on information that is provided to it by way of a fingerprint that contains many attributes of the file being processed. This fingerprint is sent along with the Secure Hash Algorithm (SHA-256) hash of the file in the initial message to the cloud.

  - Ethos is a fuzzy logic-based malware detection engine. Ethos also resides in the cloud, and is invoked if the file being checked is not known or returns a neutral disposition.

2. Client Connector: This is the component that runs on the endpoints. It communicates with the cloud to send information about files and to receive file disposition information.

3. Cisco AMP for Endpoints Mobile: An application that you can install on a mobile device to communicate with the cloud for detection of mobile malware. Currently, only the Android operating system is supported. Cisco AMP for Endpoints Mobile is supported on Android 2.1 and higher.

4. Cisco AMP for Endpoints Mac Connector: Supports Apple devices running OS X 10.7 or greater. This connector has a limited graphical interface that you can access from the menu bar if you choose it as an installation option in the Mac policy.

5. AMP for Networks: Gives Firepower devices the ability to query the cloud to obtain file disposition information on files that are detected by the Firepower device.
