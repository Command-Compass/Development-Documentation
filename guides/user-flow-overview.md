### User Flow Overview

1. **Entry Points**:
   - **Home Page**: The starting point for all users. Links to various informational and functional pages.

2. **Informational Pages** (Accessible without login):
   - **About Us Page**: General information about the website or company.
   - **Contact Us Page**: Means for users to get in touch with support or inquiries.
   - **Terms Page**: Legal information and terms of service.

3. **Authentication Flow**:
   - **Login Page**: 
     - Users can enter their credentials to access their account.
     - If the login is successful, the system sets an authorization token and user ID in a cookie.
     - Redirects to the User Profile page.
   - **Signup Page**:
     - New users can create an account by providing required information.
     - After successful signup, the system sets an authorization token and user ID in a cookie.
     - Redirects to the User Profile page.
   - **Navigation**:
     - Both Login and Signup pages link back to the Home Page.
     - Users can switch between Login and Signup pages as needed.

4. **Authenticated User Flow**:
   - **User Profile**:
     - Accessible after successful login or signup.
     - Allows users to view and manage their personal information and settings.
   - **Profile Button**: Available on the Home Page once the user is logged in, linking to the User Profile.

5. **Service Access**:
   - **Get Started Page**: Central hub for accessing various services.
     - **Command Selection Page**:
       - Users can choose specific commands or services.
       - **Worker Page**: Specialized services for certain user roles or functions.
       - **LLM Page**: Access to language model-related functionalities.

### Conditional Navigation Based on User Status

- **Non-logged-in Users**:
  - Can browse informational pages (About Us, Contact Us, Terms).
  - Can navigate to Login or Signup pages.
  - **Get Started Page** might prompt them to log in for further access.

- **Logged-in Users**:
  - Have access to their User Profile.
  - Can access personalized content and advanced services directly.
  - Can use the Profile Button to quickly return to their profile.

### Notes and Annotations:

- **Sticky Notes**: Highlight important steps and current free services.
- **Important Steps**: Emphasis on logging in or signing up to access full functionality.

### Key Interactions Summary:

- **Starting Point**: Users land on the Home Page.
- **Informational Browsing**: Users can view About Us, Contact Us, and Terms pages.
- **Authentication**: Users can log in or sign up, leading to access to their User Profile.
- **Service Access**: From the Get Started Page, users can select and use specific commands, directed to appropriate service pages.