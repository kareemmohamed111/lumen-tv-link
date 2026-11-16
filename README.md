# Lumen TV — phone sign-in

Companion page for the Lumen TV Samsung app. Scan the QR code on the TV sign-in screen to open it.
Login details are encrypted on the phone (AES-GCM) with a key that only exists in the QR code and are relayed to the TV via ntfy.sh as ciphertext.
