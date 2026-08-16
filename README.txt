GANPATI AR WEBPAGE

This is the webpage shell for the Ganpati image-tracking AR project.

Folder contents needed:
- index.html
- targets.mind       <- compiled tracking target made from your 18x18 cm pattern
- ganpati.glb        <- your Ganpati 3D model

The page uses MindAR image tracking and A-Frame.
The QR code should point to the public URL of this folder after it is hosted.

Important:
Opening index.html directly as a local file may not allow camera access.
Host it on a secure HTTPS website before testing on a phone.

The target image must be compiled into a .mind file. The HTML cannot use the raw PNG/JPG as the MindAR target.
