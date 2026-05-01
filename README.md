# WoltLab Latest Topics

**WoltLab Latest Topics** is a Joomla site module that displays the latest topic titles from a WoltLab Suite RSS/Atom feed.

It is designed for Joomla 6.x and provides a simple, lightweight way to show recent forum activity on a Joomla website without requiring a full user bridge or SSO integration.

## Features

- Displays latest topics from a WoltLab Suite RSS/Atom feed
- Supports RSS and Atom feed formats
- Configurable topic limit
- Optional topic date display
- Optional author display
- Optional category badge
- Optional “New” badge
- Optional “All Topics” button
- Joomla/Bootstrap-friendly output
- Lightweight frontend markup
- Joomla cache support
- Multilingual language files:
  - English
  - Turkish

## Requirements

- Joomla 6.x
- PHP 8.2 or newer
- A publicly accessible WoltLab Suite RSS/Atom feed URL

## Installation

1. Download the latest release package:

   `mod_woltlab_latest_topics_v1.2.2.zip`

2. Go to your Joomla Administrator panel.

3. Open:

   `System → Install → Extensions`

4. Upload and install the ZIP package.

5. Go to:

   `Content → Site Modules`

6. Open **WoltLab Latest Topics**.

7. Configure your WoltLab feed URL and publish the module.

## Configuration

The module provides the following options:

### Forum Feed URL

The RSS or Atom feed URL of your WoltLab Suite forum.

Example:

```text
https://www.example.com/feed/
