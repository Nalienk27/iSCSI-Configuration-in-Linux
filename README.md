# iSCSI-Configuration-in-Linux
I created a detailed SOP demonstrating how to build a network-based block storage solution using iSCSI, converting a standard Linux server into a storage provider.

What This SOP Covers
🖥 Target Server (Storage Side)

✔ Disk identification and preparation
✔ Creating backstore (storage object)
✔ Configuring iSCSI Target (IQN)
✔ LUN setup and mapping
✔ Access control (ACL configuration)
✔ Firewall configuration for iSCSI (port 3260)

💻 Initiator Server (Client Side)

✔ Installing iSCSI initiator tools
✔ Configuring initiator name
✔ Discovering available targets
✔ Logging into iSCSI target
✔ Verifying newly attached disk
✔ Creating filesystem on iSCSI disk
✔ Manual and automatic mounting (fstab)
