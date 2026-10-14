# KIXORA Screen Specifications

All screens use the KIXORA dark navy design system. Mobile bottom navigation is consistent on Home, Clips, Explore, Messages, and Profile.

## 1. Welcome & Authentication
- KIXORA mark and wordmark, tagline “Connect. Share. Belong.”
- Hero visual: abstract connected globe / luminous network.
- Primary CTA: Create Account.
- Secondary CTA: Log In.
- Optional social sign-in buttons, legal links.
- Keep this screen welcoming, not overloaded.

## 2. Home Feed
- Header: KIXORA logo, search, notifications, avatar.
- Stories row with “Your Story” and user stories.
- Composer: “What’s on your mind?” with Photo, Video, and Live actions.
- Feed cards: avatar, display name, timestamp, post text, image/video, reaction counts.
- Like, Comment, Share actions.
- Use sample content for preview; real feed needs a backend.

## 3. KIXORA Clips
- Full-height vertical video area.
- Following / For You switch and search.
- Right-side stack: Like, Comment, Share, sound.
- Bottom overlay: creator name, Follow button, caption, hashtags, audio attribution.
- Keep overlays readable against video with subtle gradients.

## 4. Explore & Trending
- Search field at top.
- Trending topics chips (e.g., #Africa, #Music, #Tech, #Lifestyle).
- Popular creators row.
- Image/video discovery grid.
- Optional category filters and “See all” actions.

## 5. Messages
- Title and compose icon.
- Search messages field.
- Tabs: All, Direct, Groups, Requests.
- Conversation rows with avatar, name, last message, time, unread badge.
- Conversation detail page should support text, media attachment, delivery/read states after backend implementation.

## 6. Communities
- Search communities field.
- Discover / My Communities tabs.
- Create Community card.
- Recommended group rows with title, category, member count, and Join button.
- Group detail page can later include posts, members, events, and moderation.

## 7. Notifications
- Filter chips: All, Likes, Comments, Follows.
- Activity rows with avatar, clear action description, time, and optional preview thumbnail.
- Unread items use a subtle surface highlight, not colour alone.

## 8. Profile
- Cover image and avatar.
- Display name, username, optional verification marker.
- Bio and profile actions.
- Stats: Posts, Followers, Following.
- Tabs: Posts, Reels, Tagged.
- Edit Profile action for the owner.

## 9. Settings
- Profile summary row.
- Account, Privacy & Security, Notifications, Appearance, Language, Data Saver, Help & Support, About KIXORA.
- About screen includes “Designed by Kitsamba Joshua”.
- Include dark/light theme control if the app will support both.

## Shared navigation
Bottom bar items: Home, Clips, Explore, Messages, Profile. Communities and Notifications can be reached from Home header/profile menu or a wider-screen sidebar.

## Suggested build order
1. Design tokens and reusable components.
2. Home Feed and bottom navigation.
3. Explore, Messages, Profile.
4. Clips, Communities, Notifications, Settings.
5. Authentication and onboarding.
6. Backend, validation, permissions, error states, and testing.
