# Shhh11
Windows Privacy Script
Overview

A Windows privacy and system optimization script designed to reduce telemetry, disable unnecessary background services, remove bundled applications, modify privacy settings, and improve user control over Windows features.

The script creates registry backups before applying changes.

Features
Registry Backup

Creates backups of:

HKEY_CURRENT_USER
HKEY_LOCAL_MACHINE

Backup files are saved as:

WindowsPrivacyBackup_DATE_TIME_HKCU.reg
WindowsPrivacyBackup_DATE_TIME_HKLM.reg
Service Management

Disables selected Windows services related to:

Telemetry collection
Diagnostic tracking
Error reporting
Delivery Optimization
Xbox services
Remote services
Background synchronization
Location services
Device discovery
Push notifications
Scheduled Task Management

Disables scheduled tasks related to:

Windows telemetry
Compatibility analysis
Feedback collection
Diagnostic reporting
Data collection
Automatic suggestions
Background maintenance tasks
Privacy Registry Tweaks

Applies registry changes to reduce:

Windows telemetry
Diagnostic data collection
Advertising ID tracking
Personalized suggestions
Activity history
Cloud synchronization
Search recommendations
Web search integration
Cortana features
Windows Copilot features
AI-related data collection
Delivery Optimization

Changes Windows update delivery settings:

Disables peer-to-peer update sharing
Disables Microsoft cache servers
Limits background update distribution
Search and Cortana

Modifies Windows Search settings:

Disables Bing search integration
Disables web search results
Disables search suggestions
Disables Cortana integration
Disables search history features
Microsoft Account Synchronization

Disables synchronization features:

Personalization sync
Browser settings sync
Credential sync
Language sync
Application sync
Start menu layout sync
Content Suggestions Removal

Removes Windows promotional content:

Start menu suggestions
Lock screen recommendations
Suggested applications
Advertising content
Consumer experience features
Windows AI and Copilot

Disables:

Windows Copilot
AI analytics
Snapshot features
AI-related data processing
Permission Management

Modifies Windows application permissions:

Location access
Camera access
Microphone access
Contacts access
Calendar access
Notification access
Diagnostic data access
Input and Speech Privacy

Disables:

Typing personalization
Ink personalization
Speech personalization
Online speech features
Gaming Features

Disables:

Xbox Game Bar recording
Game DVR
Broadcasting features
OneDrive Removal

Removes:

OneDrive startup entry
OneDrive installation
Microsoft Edge Privacy Settings

Changes Edge policies:

Disables telemetry reporting
Disables personalization reporting
Disables shopping features
Disables recommendations
Disables sidebar features
Removes new tab content
Disables search suggestions
Diagnostic Logger Changes

Disables selected Windows diagnostic logging systems:

AutoLogger services
Performance diagnostics
Telemetry event collectors
Hosts File Blocking

Adds telemetry-related domains to the Windows hosts file:

Examples:

telemetry.microsoft.com
v10.events.data.microsoft.com
v20.events.data.microsoft.com
watson.telemetry.microsoft.com

Used to block connections to selected tracking and diagnostic endpoints.

Security Feature Configuration

Changes Microsoft security-related settings:

SmartScreen configuration
Defender cloud reporting settings
Sample submission settings
Defender monitoring policies
Application Removal

Removes selected built-in Windows applications:

Examples:

Xbox applications
Bing applications
News
Weather
Solitaire
Phone Link
Feedback Hub
Preinstalled Microsoft applications
Supported System

Designed for:

Windows 10
Windows 11
Administrator privileges required potentially system privileges via PSTOOLS
Windows operating system
Main Components
Registry modification
Service configuration
Scheduled task management
AppX package removal
Hosts file modification
Windows policy configuration
Privacy setting adjustments
