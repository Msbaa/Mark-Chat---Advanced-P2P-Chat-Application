# Mark-Chat---Advanced-P2P-Chat-Application
A feature-rich peer-to-peer (P2P) chat application built with C# and .NET WinForms, designed for secure, direct communication without relying on central servers. Mark Chat combines modern UI design with robust networking capabilities to deliver a professional messaging experience.  🚀 Key Features

🚀 Key Features
💬 Real-Time Communication
Instant Messaging: Direct peer-to-peer text communication

File Transfer: Send files of any size with real-time progress tracking

Message History: Color-coded chat interface with timestamps

Sound Notifications: Audio alerts for new messages and file transfers

🔐 Security & Privacy
AES-256 Encryption: Optional end-to-end message encryption

No Central Server: Complete privacy with direct P2P connections

Local Data Storage: All chat history stored locally on your device

Secure File Transfer: Encrypted file transmission support

👤 Profile Management
Custom Profiles: Set display names and upload profile pictures

Auto-Generated Avatars: Automatic initial-based profile pictures when no image is set

Profile Persistence: User data saved locally for consistent identity across sessions

Bio Support: Add personal status messages and descriptions

🌐 Advanced Connectivity
Dual Mode Operation: Act as server (host) or client (join) seamlessly

International Support: Connect globally using VPN networks or port forwarding

Connection Quality Monitoring: Real-time ping display and connection status

Auto-Retry Logic: Enhanced connection reliability with automatic reconnection

Public IP Detection: Automatic external IP discovery for easy connection sharing

🎨 Modern Interface
Dark Theme: Professional dark UI with blue accent colors

Minimalist Design: Clean, distraction-free chat interface

Custom Title Bar: Drag-to-move functionality with modern window controls

Responsive Layout: Well-organized sidebar and main chat areas

Progress Indicators: Visual feedback for file transfers and connection status

⚙️ Customizable Settings
Encryption Toggle: Enable/disable message encryption as needed

Sound Control: Configurable audio notifications

Auto-Scroll: Optional automatic chat scrolling

Theme Options: Light and dark mode support

Connection Preferences: Customizable timeouts and retry settings

🛠️ Technical Specifications
Framework: .NET 6+ with Windows Forms

UI Library: Guna.UI2 for modern, professional controls

Networking: TCP sockets with async/await patterns for optimal performance

Encryption: AES-256 encryption with configurable keys and IV

File Handling: Chunked file transfer with progress tracking and resume capability

Data Storage: JSON-based local configuration and profile storage

Threading: Multi-threaded architecture for responsive UI and network operations

🌍 Connection Methods
Local Network
Simple IP address connection within the same network

Perfect for office, home, or LAN party communication

Internet (Global)
VPN Networks: Use Hamachi, Radmin VPN, or similar for easy setup

Port Forwarding: Configure router for direct internet connections

Cloud Hosting: Deploy on cloud platforms for always-available chat servers

International Optimization
Enhanced connection timeouts for international links

Connection quality monitoring with ping statistics

Automatic retry logic for unstable connections

Support for multiple connection methods as fallback options

📋 Getting Started
Prerequisites
Windows 10/11

.NET 6.0 Runtime or higher

Network connection (local or internet)

Quick Start
Host a Session: Set port (default 8080), click "Start Server", share your IP

Join a Session: Enter host IP and port, click "Connect"

Start Chatting: Send messages and files instantly!

International Setup
Download Hamachi VPN for easiest international connections

Or configure router port forwarding for direct access

Use built-in IP detection tools for easy address sharing

🎯 Use Cases
Private Communication: Secure chats with friends and family

Small Team Collaboration: Direct team communication without third-party services

Gaming Communities: Coordination for gaming sessions and events

Educational Projects: Learn networking, encryption, and GUI development

Privacy-Conscious Users: Those who prefer P2P over centralized platforms

International Communication: Connect with people worldwide using VPN networks

🔒 Privacy & Security
Zero Data Collection: No telemetry, analytics, or user data harvesting

Local Storage Only: All data remains on your device

Optional Encryption: Choose when to encrypt sensitive conversations

Direct Connections: No intermediary servers to compromise privacy

Open Source: Full transparency with publicly available source code

📊 Performance
Low Resource Usage: Minimal CPU and memory footprint (~50MB RAM)

Fast File Transfer: Efficient chunked transfers with speeds up to network limits

Reliable Connections: Robust error handling with automatic recovery

Scalable Design: Handles multiple simultaneous connections efficiently

🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page or submit pull requests.

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments
Guna Framework for beautiful, modern WinForms controls

.NET Team for the excellent development framework

Open Source Community for inspiration and best practices

