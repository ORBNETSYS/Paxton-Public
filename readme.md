# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),

## [2.0.7] - 19.02.2022

- Added: Door state polling instead of SignalR
- Update: Added new door icons for Open Locked Alarm, Open Unlocked Alarm, Close Locked Alarm and Closed Unlocked Alarm.
- Fix: Polling the last 3000 events instead of the last 100 events every second.
- Removed: SignalR for state changes
