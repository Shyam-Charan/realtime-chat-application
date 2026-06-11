# Architecture

## Components

### Client Layer
Handles user connections and message sending.

### Server Layer
Manages multiple client connections and message broadcasting.

### Room Manager
Organizes clients into chat rooms.

## Data Flow

Client → WebSocket → Server → Broadcast → All Clients
