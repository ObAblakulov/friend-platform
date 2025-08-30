# FriendZone

**A React Native social app built with Expo**  
Helps people make friends based on shared interests with anonymous posting real time chat and location based discovery

## Overview

FriendZone blends familiar social features with anonymous interactions and location discovery to help users find and build friendships not just followers. The app supports image and video posts anonymous voting real time messaging and an interactive map for discovering nearby people and events

Repository purpose  
A polished project to showcase production style mobile engineering for competitive SWE roles


## Request a TestFlight demo or codebase preview 

Email to request a TestFlight demo or additional information: ablakulovoybek@gmail.com 


## Tech stack

Frontend
* React Native with Expo
* Expo Router for file based navigation
* react native maps for map features
* react native fast image for optimized image handling
* react native render html for rich content

Backend and Database
* Supabase for Auth Postgres storage and real time subscriptions
* PostgreSQL with Row Level Security for per row access control
* Supabase Storage for media management

Libraries and Utilities
* Moment.js for date and time formatting
* react native image picker for media selection
* react native video for video playback
* AsyncStorage for local persistence


## Key features

### Social
* Customizable user profiles with interest tags and personal info
* Friend system with friend codes for quick connections
* Public posts and friend only posts with image and video support
* Anonymous posting with upvotes and downvotes

### Messaging and Groups
* Real time direct messaging with read receipts and typing indicators
* Anonymous chat rooms and group messaging
* Media sharing inside chats

### Discovery and Interaction
* Interactive map for location based discovery
* Interest matching to suggest compatible users
* Events creation discovery and RSVP
* Push and in app notifications for messages requests and activity

### Privacy and Safety
* Optional anonymous interactions for privacy focused users
* Supabase Auth for secure authentication
* Row level security on the database for per user access control
* Clear privacy policy and terms of service integration


## Core functionality

* Authentication and onboarding with email password sign up interest selection academic info optional and privacy consent
* Feed that combines posts and events with anonymous voting and friend only content
* Messaging that supports live chat between friends and anonymous rooms with media sharing and read receipts
* Matching that uses selected interests to calculate compatibility scores and surface potential connections


## Code organization and guidelines

* Components grouped by feature and reusability
* Services handle Supabase API interactions
* Contexts manage global state for auth onboarding and navigation
* Constants define theme and configuration values
* Follow existing style and test changes on both platforms before creating PRs

## Security considerations

* Row Level Security in Supabase to enforce per user access
* Secrets kept in environment variables and never committed
* Anonymous flows minimize personally identifying data

## For recruiters and hiring managers

Why FriendZone is recruiter friendly
* Real time app architecture using Supabase subscriptions and a mobile client
* Security best practices implemented with RLS and proper auth
* Location services and maps integration for production grade mobile features
* Media handling and performance work including optimized image delivery and storage
* Clear separation of services contexts and reusable UI components

If you want a guided demo mention which area to focus on when you reach out for example messaging map discovery or anonymity workflows

## Contributing

When contributing follow these steps
1. Follow the repository style and folder structure
2. Test changes on iOS and Android and include device and OS in PR descriptions
3. Validate real time flows and RLS changes locally before submitting
4. Update documentation for significant feature or architectural changes
5. Consider privacy implications for new features

## License and ownership

Developed by Mooruz LLC  
Contact for licensing and partnership details

