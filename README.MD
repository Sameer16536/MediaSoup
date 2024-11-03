## Project Setup

```bash
cd backend
npm install

cd frontend
npm install
```

## About the project

We are creating a video chat application using the following technologies:

-   Typescript
-   Node.js
-   Express
-   websocket
-   Mediasoup
-   React
-   Tailwind CSS
-   WebRTC
-   Postgres
-   Prisma

## Project Structure

-   `backend`: Contains the server code.
-   `frontend`: Contains the client code.

## Application Flow

The application follows this logical flow:

1. **Authentication Flow**
   - Users can either login or signup
   - Authentication token is verified for protected routes
   - Successful login redirects to home page

2. **Room Management**
   - Authenticated users can create new rooms
   - Users can join existing rooms
   - Each room supports WebRTC peer connections

3. **Video Chat Features**
   - ICE candidate exchange for peer connection
   - SDP (Session Description Protocol) handling
   - Remote and local media stream management
   - Screen sharing capabilities
   - Mediasoup for media routing

4. **Database Integration**
   - User data managed through Prisma ORM
   - Persistent storage in PostgreSQL

## Logic 
 ![alt text](image.png)
