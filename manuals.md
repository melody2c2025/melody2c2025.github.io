---
layout: default
title: Melody
description: Guides & Manuals.
---

## Content

* [Installation Guide](#installation-guide)
* [User Manual: Mobile App](#user-manual-mobile-app)
* [Feature Overview](#feature-overview)

## Installation Guide

### Mobile Application

#### Android
Download the latest APK from our releases page: [**download**](https://github.com/melody2c2025/frontEnd-melody/releases)\
Install the APK on your Android device.\
**Minimum version**: Android 8.0 (API level 26) or higher

#### iOS
Coming soon. Stay tuned for TestFlight beta access.

### Requirements
- Stable internet connection
- Permissions for storage (to save downloaded content)
- Permissions for notifications (to receive updates)

## User Manual: Mobile App

### Getting Started

#### 1. Register & Login
- **Sign up** with email and password or use Google authentication
- Choose your account type: **Oyente** (Listener) or **Artista** (Artist)
- Complete the onboarding process to set your favorite genres and artists

#### 2. Onboarding
After registration, you'll be guided through:
- **Genre selection**: Pick your favorite music genres
- **Artist discovery**: Follow artists you love
- **Notification preferences**: Choose what updates you want to receive

### Main Features

#### Home
- Discover new releases, shortcuts to your favorite content
- Personalized recommendations based on your taste
- Quick access to Made For You playlists

#### Search
- Unified search across songs, albums, playlists, and artists
- Recent searches and popular searches
- Instant results as you type

#### Library
- **Playlists**: Create and manage your own playlists
- **Liked Songs**: All your favorite tracks in one place
- **History**: See what you've been listening to
- **Albums & Artists**: Your saved collections

#### Player
- Full-featured music player with:
  - Play, pause, skip, shuffle, repeat
  - Queue management (view and reorder upcoming songs)
  - Lyrics display (when available)
  - Video playback for music videos
- Mini player for navigation while browsing
- Mark songs as liked directly from the player

#### Profile
- View and edit your profile information
- See your public activity and playlists
- Follow/unfollow other users
- View listening statistics

### Features for Artists

#### Artist Profile Management
- Upload profile picture and banner
- Edit bio and social media links
- Set up Artist Pick (featured content)
- Add photo carousel to your About section

#### Publishing Releases
- Upload singles, EPs, and albums
- Add metadata: title, genres, credits, cover art
- **Fast Complete (AI)**: Auto-fill metadata from artist and title
- Schedule releases or publish immediately
- Set regional availability

#### Discography
Your artist profile automatically organizes:
- **Popular**: Your top tracks
- **Releases**: All your albums, EPs, and singles
- **Appears On**: Collaborations and playlist features

### Social Features

#### Following
- Follow other users and artists
- See what your friends are listening to in real-time
- Activity feed shows recent plays and likes

#### Sharing
- Share songs, albums, and playlists
- Internal sharing within the app
- External sharing to social media

### AI-Powered Features

#### Mood Mixes
- AI-generated playlists based on your mood and context
- Automatic updates based on time of day and listening habits

#### Radio by Song
- Start a radio based on any song
- Discover similar tracks and artists

#### Auto Play
- Seamless listening experience
- AI continues playing similar music when your queue ends

### Notifications
- New releases from artists you follow
- Activity from friends (likes, new playlists)
- Tap notifications to jump directly to content (deep linking)

### Settings & Preferences
- Manage notification preferences
- Content filters (explicit content on/off)
- Audio quality settings
- Privacy settings for profile and playlists

## Feature Overview

### Implemented Features

#### Users & Profile (Épica: Usuarios y Perfil)
- ✅ Registration with email/password
- ✅ Login with email/password
- ✅ Login with Google (federated provider)
- ✅ Password recovery
- ✅ Profile editing
- ✅ View own profile
- ✅ View other users' profiles

#### Artists (Épica: Artistas)
- ✅ Artist profile with stats and bio
- ✅ Discography: Popular (top 5), Albums, Singles & EPs
- ✅ Collaborations (Appears On)
- ✅ Artist profile management
- ✅ Release publishing (singles, EPs, albums)
- ✅ Song metrics (plays, likes, shares)
- ✅ Album metrics
- ✅ Artist metrics (monthly listeners, followers)

#### Content Management - Admin (Épica: Adm. Contenido)
- ✅ Catalog explorer with search
- ✅ Content detail and traceability
- ✅ State transitions and effective status
- ✅ Block/unblock content with scope (global/regional)

#### User Management - Admin (Épica: Adm. Usuarios)
- ✅ List all users
- ✅ View user profile details
- ✅ Block/unblock users
- ✅ User activity metrics with export

#### Explore (Épica: Explorar)
- ✅ Home: shortcuts, new releases from followed artists, recently played, discover more
- ✅ Unified search by type (songs, albums, artists, playlists, profiles)
- ✅ Navigate to detail views for all content types

#### Playback (Épica: Reproducción)
- ✅ Basic playback controls (play, pause, skip, previous)
- ✅ Advanced controls (seek/scrub, repeat modes, shuffle)
- ✅ Queue management (view, reorder, clear)
- ✅ Like/unlike songs from player
- ✅ Music video support (when available)

#### Library (Épica: Biblioteca)
- ✅ Create and manage playlists
- ✅ Reorder playlist content (drag and drop)
- ✅ Playback history
- ✅ Liked Songs collection

#### Social (Épica: Social)
- ✅ Follow user profiles
- ✅ View friends' activity with filters
- ✅ Share songs and playlists (internal and external)

#### Notifications (Épica: Notificaciones)
- ✅ Push notifications for new content from followed artists
- ✅ Notifications for activity from followed users
- ✅ Deep linking: tap to navigate directly to content

#### Onboarding (Épica: Onboarding)
- ✅ Select favorite genres during first login
- ✅ Select favorite artists during first login

---

For technical details and API documentation, visit the **Technical Documentation** section.
