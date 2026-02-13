# User Flows – Sorbit

## 1. Account Creation & Login Flow

- User visits the home page.  
- Two options: "Sign Up" or "Log In."  
- If "Sign Up," user enters name, email, password (minimal fields).  
- If "Log In," user enters email, password.  
- After successful login, user lands on the dashboard.  
- The system remembers the login state, so on future visits, no need to log in again.

## 2. Dashboard Flow

- After login, user lands on a clean dashboard with no clutter.  
- At the top, a prominent “Add Account” button.  
- Dashboard shows a summary: number of accounts linked, last post date, and basic analytics like engagement numbers.  
- From the dashboard, user can:  
  - Click “Add Account” to link a new social profile.  
  - Click any listed account to see platform-specific analytics.  
  - Click “Create Post” to start a new content piece.

## 3. Add Account Flow

- User clicks "Add Account" button.  
- List of platforms (Facebook, TikTok, YouTube, LinkedIn) is displayed.  
- User selects a platform.  
- For OAuth: user is redirected to platform login screen, grants permissions, returns to dashboard linked.  
- For manual: user enters credentials (email + password).  
- Once added, account status is shown on dashboard.

## 4. Create Post Flow

- User clicks “Create Post.”  
- Post form opens: user selects which linked accounts they want the post to go to.  
- User enters text—real-time character limits for each platform (e.g., Twitter max 280, LinkedIn, etc.).  
- Optional: user uploads an image (ensure universal size limit, e.g., 5 MB).  
- After input, user clicks “Schedule” or “Post Now.”  
- If “Post Now,” the post is immediately sent to chosen platforms.  
- If “Schedule,” user picks date/time, then saves the post.  
- After posting, user returns to dashboard, sees confirmation, and a record of the post.

## 5. Returning User Flow

- User revisits the site (logged in automatically).  
- Dashboard loads with all previous linked accounts still intact.  
- User can create new posts, view analytics, and manage content all from one place.

## 6. Key Considerations

- No admin panel—user is always a creator.  
- Keep all flows linear—no more than 3 clicks for any major action.  
- Character and image limits are enforced in real time—no confusion.  
- Dashboard is the user’s anchor—everything loops back there for simplicity.

