<p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>

Peer2PeerNoteSharing

## Basic Details

### Team Name: EDUTEAM

### Team Members
- Member 1:Arya C Vinu - Sree Narayana Gurukulam College Of Engineering, Kadayiruppu
- Member 2:Sreelakshmi T J - Sree Narayana Gurukulam College Of Engineering, Kadayiruppu

### Hosted Project Link
https://aryacv.github.io/Peer2PeerNoteSharing/

### Project Description
A decentralized, privacy-focused note-sharing platform that allows students to discover and transfer study materials directly between browsers. By using WebRTC, files never touch a central server, ensuring high-speed transfers and total data ownership.

### The Problem statement
Traditional file-sharing sites often require accounts, have file size limits, or store your private data on their servers. Students need a quick, "no-strings-attached" way to swap notes during lectures or study sessions without relying on a middleman.

### The Solution
We built a true P2P marketplace. Users connect via unique Student IDs. Once a link is established, the browsers automatically exchange "Metadata" (a list of available notes). Users can then browse their peer's library and "beam" files directly from one device to another.

---

## Technical Details

### Technologies/Components Used

**For Software:**
- Languages used: HTML5, CSS3, JavaScript (ES6+)
- Frameworks used: Tailwind CSS (UI Styling)
- Libraries used: PeerJS (WebRTC Wrapper for P2P connectivity)
- Tools used: VS Code, Git, GitHub Pages


## Features
Direct P2P Transfer: Files are sent directly between users using WebRTC DataChannels.

Automated Discovery: As soon as two peers connect, they automatically exchange their "Note Manifest" so users can see what is available.

No Server Storage: Files stay on the sender's device until the receiver requests them; no data is ever uploaded to a cloud.

Privacy by Design: End-to-end encrypted tunnels ensure that only the sender and receiver can see the content being transferred.


## Implementation

### For Software:

#### Installation
```bash
git clone https://github.com/aryacv/Peer2PeerNoteSharing.git
#### Run
```bash
cd Peer2PeerNoteSharing



## Project Documentation

### For Software:
The main landing page where a user generates their unique Peer ID.

The Marketplace view showing notes available on the connected peer's device.

The UI during an active file transfer showing the "Note Vault" updates.

#### Screenshots (Add at least 3)

![Screenshot1](Add screenshot 1 here with proper name)
*Add caption explaining what this shows*

![Screenshot2](Add screenshot 2 here with proper name)
*Add caption explaining what this shows*

![Screenshot3](Add screenshot 3 here with proper name)
*Add caption explaining what this shows*

#### Diagrams

**System Architecture:**
The architecture uses a Signaling Server (PeerJS) only for the initial handshake. Once the IDs are exchanged, a direct WebRTC DataChannel is established for binary file transfer.

**Application Workflow:**
1. User A adds files to Vault -> 2. User B connects to User A -> 3. Manifests are exchanged -> 4. User B requests file -> 5. Direct Transfer.

## Project Demo

### Video
[Add your demo video link here - YouTube, Google Drive, etc.]

*Explain what the video demonstrates - key features, user flow, technical highlights*

### Additional Demos
[Add any extra demo materials/links - Live site, APK download, online demo, etc.]

---

## AI Tools Used

**Tool Used:Gemini 3 Flash / ChatGPT

**Purpose:**
-Debugging WebRTC connection listeners.

Generating the responsive Tailwind CSS "Glassmorphism" UI.

Structuring the PeerJS MANIFEST exchange logic.

Percentage of AI-generated code: 40%

**Human Contributions:**
    Project idea and P2P logic flow.
    UI/UX design decisions and color palette.
    Testing across different network environments (Wi-Fi vs Mobile Data).
    Documentation and project structure.


## Team Contributions
  Arya C Vinu: Core P2P logic implementation, PeerJS integration, and Backend-to-Frontend data     mapping.
  Sreelakshmi T J: Frontend UI design with Tailwind CSS, Responsive layout optimization, and Project   Documentation.

---

## License
This project is licensed under the MIT License.

Made with ❤️ at TinkerHub
