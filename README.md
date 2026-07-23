# SimpleRadioPlayer 📻

**SimpleRadioPlayer** is a modern and professional Android application for listening to radio streams from all over the world. Designed with an aesthetic reminiscent of vintage and broadcast audio consoles, it offers advanced technical tools for real-time signal quality monitoring.

## 🚀 Main Features

### 🎶 Professional Audio Streaming
- **Media3 ExoPlayer Engine**: Uses the latest Google libraries for smooth, low-latency streaming.
- **Foreground Service**: Music continues playing in the background even if you close the app, with media controls in the notification shade and lock screen.
- **Smart Search**: Integrated database with thousands of stations, sortable by popularity or searchable by name.

### 📊 Technical Monitoring (Dashboard)
- **Analog S-Meter**: A real needle instrument that measures "Signal Strength" based on buffer health.
- **Digital LCD Display**: Real-time visualization of:
    - **Bitrate**: Stream quality (e.g., 128kbps, 320kbps).
    - **Format**: Audio codec (MP3, AAC, etc.).
    - **Buffer Health**: Seconds of pre-downloaded buffer to prevent interruptions.

### 🚗 Car Mode
- **Always-On**: The app detects if the device is connected to a power source (USB or car charger) and keeps the display always on, ideal for dashboard use while driving.

### ⭐ Advanced Favorites Management
- **Quick Bar**: Immediate access to favorite stations below the technical dashboard.
- **Drag & Drop**: Reorder your favorite stations by simply dragging them.
- **Gesture Management**: Remove favorites with an upward or downward swipe.

### 🛠️ OEM & UX Optimizations
- **Xiaomi Guide**: Integrated tutorial to configure battery saving on Xiaomi/POCO devices to avoid system interruptions.
- **Bilingual Welcome**: Comprehensive welcome dialog in Italian and English to guide new users.
- **Adaptive Icon**: Modern design with an integrated mini VU-meter that adapts to every Android interface.

## 🛠️ Technical Stack
- **Language**: Java / Android SDK
- **Player**: Jetpack Media3 (ExoPlayer)
- **Network**: OkHttp 4
- **Image Loading**: Glide
- **UI**: Custom Views using Canvas API for analog instruments.

---
*Developed by MARINOLAB*

