# Flumers.AI

## Project Overview
Flumers.AI is a next-generation influencer marketing platform that connects brands and influencers. The platform enables influencer discovery, real-time chat between real users (brands and influencers), order management, and user profiles. All chat features now exclusively support real users—no automated or bot accounts are present in the system.

## Folder Structure
```
public/
  favicon.ico
  index.html
  logo192.png
  logo512.png
  manifest.json
  robots.txt
src/
  api/
    api.js
    auth.js
    firebaseConfig.js
    supabaseConfig.js
  auth/
    authSlice.js
    Login.js
    Signup.js
  components/
    HomePage.js
    Navbar.js
    SelectRole.js
    UserInfo.js
  features/
    chat/
      BrandChats.js
      FloatingChatbot.js
      InfluencerChats.js
    profile/
      BrandDashboard.js
      BrandOrders.js
      BrandProfile.js
      InfluencerDashboard.js
      InfluencerOrders.js
      InfluencerProfile.js
      profileSlice.js
      SearchInfluencers.js
      ShowProfile.js
      UserProfile.js
  routes/
    ProtectedRoute.js
  styles/
    theme.js
```

## Key Features
- Real-time chat between brands and influencers (no bots or automated accounts)
- Order creation, editing, and management
- User authentication and role-based access (brand/influencer)
- Notifications for order and chat events
- Responsive, well-documented UI with detailed code comments

## Setup Instructions
1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Start the development server with `npm start`.

## Contribution Guidelines
- Follow the folder structure and naming conventions.
- Write tests for new features.
- Ensure code is linted and formatted before committing.
- Add detailed comments to all new React components, especially for UI and CSS logic.
- Do not introduce any bot or automated user logic in chat features.

## Testing
- Run `npm test` to execute tests.

## License
This project is licensed under the MIT License.
