# WorkFlowApp

A powerful desktop automation platform built with Electron, React, and Python that enables users to create, manage, and execute complex automation workflows through an intuitive visual interface.

## 🚀 Features

### Visual Workflow Editor
- **Drag-and-drop interface** for creating automation workflows
- **Node-based architecture** with various automation capabilities
- **Real-time execution** with pause/resume functionality
- **Flow scheduling** for automated task execution
- **Public flow sharing** and community workflows

### Automation Capabilities
- **Browser Automation**: Complete web browser control with Chrome/Edge support
- **Desktop Control**: Mouse, keyboard, and window management
- **Android Control**: ADB-based mobile device automation
- **Image Recognition**: Template matching and visual automation
- **HTTP Requests**: API integration and web service calls
- **Data Processing**: Spreadsheet operations and data manipulation
- **Python Scripting**: Custom Python code execution
- **JavaScript Execution**: Client-side scripting capabilities

### Advanced Features
- **Multi-profile browser management** with proxy support
- **Screenshot and screen streaming** capabilities
- **OCR (Optical Character Recognition)** integration
- **Memory manipulation** for advanced automation
- **Loop and conditional logic** for complex workflows
- **Variable management** and data flow between nodes
- **Real-time logging** and debugging tools

## 🏗️ Architecture

### Frontend (React + Electron)
- **React 19** with CoreUI components
- **ReactFlow** for visual workflow editing
- **Monaco Editor** for code editing
- **Socket.IO** for real-time communication
- **i18n** for internationalization support

### Backend (Python)
- **Python 3.10+** with async/await support
- **Socket.IO** server for communication
- **OpenCV** for image processing
- **PyAutoGUI** for desktop automation
- **nodriver** for browser automation
- **Frida** for advanced system control

### Database
- **SQLite** for local data storage
- Flow definitions, browser profiles, schedules, and logs

## 📋 Prerequisites

- **Node.js** 18+ and npm
- **Python** 3.10+
- **ADB** (Android Debug Bridge) for mobile automation
- **Windows 10/11** (primary platform)

## 🚀 Usage

### Starting the Application

The application will launch with:
- Electron desktop window
- Python automation
- React-based user interface

### Creating Your First Workflow

1. **Open Flow Editor**: Navigate to the automation section
2. **Add Nodes**: Drag automation nodes from the sidebar
3. **Configure Nodes**: Double-click nodes to set parameters
4. **Connect Nodes**: Link nodes to create workflow logic
5. **Test & Execute**: Use the play button to run your workflow

### Available Node Types

#### Browser Automation
- **Browser Open**: Launch browser instances
- **Navigate**: Go to URLs
- **Click/Type**: Interact with web elements
- **Screenshot**: Capture browser content
- **Download**: Handle file downloads

#### Desktop Control
- **Mouse Actions**: Click, drag, scroll
- **Keyboard Input**: Type text, send keys
- **Window Control**: Manage application windows
- **Screenshot**: Capture desktop screens

#### Mobile Automation
- **Device Control**: Tap, swipe, input text
- **App Management**: Install/uninstall applications
- **Screen Capture**: Mobile device screenshots

#### Data Processing
- **HTTP Requests**: API calls and web requests
- **Spreadsheet Operations**: Excel/CSV file handling
- **Variable Management**: Store and manipulate data
- **Conditional Logic**: If/else decision making

## 🔧 Configuration

### Browser Profiles
Create and manage browser profiles with:
- Custom user agents
- Proxy settings
- Extension management
- User data directories

## 📊 Monitoring & Debugging

### Real-time Logging
- **Execution logs** for each workflow run
- **Error tracking** with detailed stack traces
- **Performance metrics** and timing information

### Debug Tools
- **Step-by-step execution** for troubleshooting
- **Variable inspection** during runtime
- **Flow state visualization**

### Android Automation
- **ADB integration** for device control
- **Screen mirroring** capabilities
- **App automation** and testing
- **Multi-device** management

## 🔄 Workflow Management

### Flow Organization
- **Categorization** and tagging
- **Version control** for flow updates
- **Import/Export** functionality
- **Template library** for common patterns

### Scheduling (Comming soon)
- **Cron-based** scheduling
- **Event triggers** for automation
- **Conditional execution** based on system state
- **Batch processing** capabilities

## 📈 Performance

- **Optimized execution** engine
- **Memory management** for large workflows
- **Concurrent processing** capabilities
- **Resource monitoring** and optimization

---

**WorkFlowApp** - Automate anything, anywhere, anytime. 🚀


- Theo dõi phiên bản mới nhất: [https://ato.io.vn](https://ato.io.vn/)
- Nếu gặp lỗi, liên hệ Facebook: [facebook.com/ato.io.vn](https://www.facebook.com/profile.php?id=61570035639741)
- Sắp tới sẽ có video hướng dẫn chi tiết tại Youtube: [youtube.com/@ato-io-vn](https://www.youtube.com/@ato-io-vn)
