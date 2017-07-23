# Kasp_update
synology package designed to automatically download AV updates and make them available for local network clients

General situation is following: My organization works in developing countries where network connectivity is either unreliable or expensive:
Current standard across sites is Synology station as file sharing server and Kaspersky Endpoint security.

Aim is to adapt Kaspersky Update utility for Linux to run at Synology station.
Utility downloads updates from Internet server to NAS at scheduled intervals.
Clients at local network will update their databases from NAS instead performing multiple downloads from Internet.
