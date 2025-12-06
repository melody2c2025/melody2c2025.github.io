---
layout: default
title: Melody
description: Technical Documentation.
---

## Technical Documentation

The complete technical documentation for Melody is available below.

You can access it via:
- **Google Docs**: [**View Documentation**](#) _(add your link here)_
- **Embedded viewer** (see below)

### Architecture Overview

**Melody** is built with a modern, scalable architecture:

#### Mobile Application
- **Framework**: React Native with Expo
- **Language**: TypeScript
- **State Management**: React Context API (PlayerContext, AuthContext)
- **Authentication**: Supabase Auth (email/password + federated with Google)
- **Navigation**: React Navigation (Stack, Tabs, Modals)
- **Audio Playback**: Expo AV
- **Notifications**: Expo Notifications with deep linking

#### Backend Services
- **Database**: Supabase (PostgreSQL)
- **API Gateway**: Custom gateway service
- **File Storage**: Supabase Storage (audio files, images)
- **Authentication**: JWT tokens

#### Key Services

The app is organized into specialized services:

- `artistService.ts`: Artist profiles and discography
- `catalogService.ts`: Content catalog management
- `playlistService.ts`: Playlist CRUD operations
- `searchService.ts`: Unified search functionality
- `feedService.ts`: Social activity feed
- `homeService.ts`: Home screen content curation
- `releaseService.ts`: Artist release management
- `notificationService.ts`: Push notifications
- `historyService.ts`: User listening history
- `likedSongService.ts`: Liked songs management

#### Main Components

**Navigation**:
- `AppNavigator.tsx`: Root navigator
- `TabNavigator.tsx`: Bottom tab navigation
- `ProfileStack.tsx`: Profile navigation flow
- `AuthNavigator.tsx`: Authentication flow

**Core Components**:
- `MiniPlayer.tsx`: Persistent mini player
- `CustomBar.tsx`: Custom app bar with search
- `SongCard.tsx`: Song display component
- `PlaylistCard.tsx`: Playlist display component
- `UserCard.tsx`: User profile card
- `FriendActivityFeed.tsx`: Social activity component

**Context Providers**:
- `PlayerContext.tsx`: Global playback state
- `AuthContext.tsx`: Authentication state

#### Project Structure

```
expo-user-management/
├── components/        # Reusable UI components
│   ├── home/         # Home screen specific
│   └── shared/       # Shared components
├── screens/          # Screen components
│   ├── main/         # Main app screens
│   └── content/      # Content detail screens
├── services/         # API services
├── hooks/            # Custom React hooks
├── lib/              # Core libraries and utilities
├── navigation/       # Navigation configuration
├── types/            # TypeScript type definitions
└── constants/        # App constants and config
```

#### Authentication Flow

1. User registers/logs in via Supabase Auth
2. JWT token is stored securely
3. Token is attached to all API requests
4. Refresh token mechanism for session management

#### Data Flow

1. **UI Layer**: React components
2. **Service Layer**: Encapsulated API calls
3. **Gateway API**: Centralized backend communication
4. **Supabase**: Database and auth
5. **Storage**: Audio files and images

#### AI Features

- **Fast Complete**: Metadata auto-completion using AI
- **Mood Mixes**: AI-generated playlists
- **Song Radio**: Similar song recommendations
- **Auto Play**: Intelligent queue continuation

### API Endpoints

All API communication goes through the Gateway API configured in `lib/gatewayApi.ts`.

Key endpoint categories:
- `/auth/*`: Authentication and registration
- `/artists/*`: Artist profiles and content
- `/songs/*`: Song operations
- `/playlists/*`: Playlist management
- `/search/*`: Search functionality
- `/feed/*`: Social feed
- `/notifications/*`: Push notifications

### Environment Configuration

The app uses environment variables for configuration:
- `EXPO_PUBLIC_SUPABASE_URL`: Supabase project URL
- `EXPO_PUBLIC_SUPABASE_ANON_KEY`: Supabase anonymous key
- `EXPO_PUBLIC_GATEWAY_API_URL`: Backend gateway URL

### Testing

- **Unit Tests**: Jest with React Native Testing Library
- **Configuration**: `jest.config.js` and `jest.setup.ts`
- **Mocks**: Located in `mocks/` and `services/mocks/`

---

_For detailed implementation, check the codebase on [GitHub](https://github.com/melody2c2025/)_

<!-- Uncomment and add your Google Docs link when ready
<iframe style="width:100%;height:800px;" src="YOUR_GOOGLE_DOCS_LINK_HERE"></iframe>
-->
