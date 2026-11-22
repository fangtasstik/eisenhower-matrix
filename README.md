# Eisenhower Matrix

A small always-on-top Windows desktop app for sorting tasks into the four Eisenhower quadrants, with a Kanban board, an inbox, an archive and a few tools (Pomodoro, weekly stats, Mermaid, Sketch). English / 中文.

This repository only hosts the installers. The source code is private.

## Install

Download `Eisenhower-Matrix-Setup-x.y.z.exe` from the [latest release](https://github.com/fangtasstik/eisenhower-matrix/releases/latest) and run it. It installs for the current user only (no admin rights) and adds a Start menu shortcut. The installer is not code-signed, so Windows SmartScreen may ask you to confirm ("More info", then "Run anyway").

## Updates

The installed app checks this repository for a new release every 4 hours, downloads it in the background, and shows a dot on the settings button. Click **Restart** to install it. Your tasks stay; they live in `%APPDATA%\Eisenhower Matrix`.
