# Troubleshooting Log

---

## Session 2 - Linux Server and SSH

### VM boots into installer upon Ubuntu installation

**When it happened**
After Ubuntu Server installation completed and the VM restarted, the VM installer started again instead of booting into the installed system.

**Cause**
The Unbuntu Server ISO was still attatched to the VM virtual optical drive.

**How I fixed it**

1. Shut down the VM (Machine > Close > Power Off)
2. Go to VM Settings > Storage
3. Click the optical drive
4. Click the small icon and select Remove Disk from Virtual Drive
5. Start the VM again

The VM booted correctly in the installed Ubuntu Server.

**How to prevent it**
During Ubuntu Server installation final steps, remove the ISO from Virtual optical drive.

**Lesson**
Always check the optical drive in Settings after a fresh installation.
