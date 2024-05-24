# Next.js YouTube API with OAuth Example

This project is an example of integrating the YouTube API with OAuth authentication in a Next.js application. It allows users to authenticate with their YouTube accounts and perform actions such as fetching playlists.

## Features

- **OAuth Authentication**: Users can sign in with their YouTube accounts using OAuth authentication.
- **Playlist Management**: Fetch playlists on the authenticated user's YouTube account.

## Technologies Used

- **Next.js**: A React framework for building server-side rendered and statically generated web applications.
- **YouTube API**: Google's API for interacting with YouTube data, including video uploads and channel management.
- **OAuth 2.0**: Authentication protocol used for authorizing access to the YouTube API on behalf of the user.

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/react-mern/Youtube-api-with-o.auth.git
   ```

2. Install dependencies:

   ```bash
   cd Youtube-api-with-o.auth
   npm install
   ```

3. Set up OAuth credentials:

   - Create a project on the Google Cloud Platform Console.
   - Enable the YouTube Data API for the project.
   - Create OAuth 2.0 credentials (OAuth client ID) and configure the authorized redirect URI to point to `http://localhost:3000/api/auth/callback`.
   - Save the client ID and client secret.

4. Configure environment variables:

   Create a `.env.local` file in the project root and add the following variables:

   ```plaintext
   NEXT_PUBLIC_CLIENT_ID=
   NEXT_PUBLIC_PROJECT_ID=
   NEXT_PUBLIC_AUTH_URI=
   NEXT_PUBLIC_TOKEN_URI=
   NEXT_PUBLIC_AUTH_PROVIDER=
   NEXT_PUBLIC_CLIENT_SECRET=
   NEXT_PUBLIC_REDIRECT_URI=
   NEXT_PUBLIC_JAVASCRIPT_ORIGINS=
   NEXT_PUBLIC_SCOPE=
   NEXT_PUBLIC_JWT_SECRET=
   NEXT_PUBLIC_BASE_URL=
   ```

5. Run the development server:

   ```bash
   npm run dev
   ```
6. Live link: https://youtube-api-o-auth.vercel.app/


Author
<p>Name: Md Kamran</p>
<p>Email: kamran@simformsolutions.com</p>
