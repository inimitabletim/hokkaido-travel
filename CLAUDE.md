# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Hokkaido 8-day family travel guide web application. It's a single-page application (SPA) designed primarily for mobile viewing, providing a comprehensive travel itinerary and useful information for a family trip to Hokkaido, Japan.

## Architecture

**Single HTML File Structure**: The entire application is contained in `index.html` with:
- Embedded CSS styles for responsive mobile-first design
- Inline JavaScript for interactive functionality
- No external dependencies or build process required

## Key Components

### Navigation System
- Tab-based navigation with sections for:
  - 行前準備 (Pre-trip preparation)
  - 交通指南 (Transportation guide)
  - Day 1-8 (Daily itineraries)
  - 美食 (Restaurants/Food)
  - 緊急 (Emergency contacts)

### Interactive Features
- `showSection(sectionId)` function handles tab switching and content display
- Responsive design optimized for mobile devices (max-width: 480px)
- Smooth animations and transitions for better user experience

## Content Structure

Each day's itinerary includes:
- Transportation details with times and costs
- Attractions with addresses, hours, and ticket prices
- Restaurant recommendations
- Tips and important reminders
- Emergency contact information

## Development Notes

- The application uses a gradient purple theme (#667eea to #764ba2)
- All text content is in Traditional Chinese (zh-TW)
- The design prioritizes readability and ease of navigation on mobile devices
- No server-side functionality required - can be deployed as a static site