# SharpChat
This is a hobby project to familairze myself with C#

# TODO - Chat Server Project

A multi-client chat server over TCP, built in C# and/or Go.

---

## Phase 1: Barebones TCP Chat

- [ ] Set up TCP server that listens on a port
- [ ] Accept multiple client connections
- [ ] Broadcast received messages from one client to all others
- [ ] Disconnect clients cleanly
- [ ] Add timestamp to messages (optional)
- [ ] Test with `telnet` or `netcat`

---

## Phase 2: Improvements & Features

- [ ] Add user nicknames (prompt user on connect)
- [ ] Broadcast join/leave messages
- [ ] Support `/nick`, `/quit`, `/help` commands
- [ ] Log all chat messages to a file
- [ ] Add private messaging support (e.g., `/msg user Hello`)
- [ ] Handle malformed input gracefully
- [ ] Add a basic client app instead of telnet

---

## Phase 3: Extended Functionality

- [ ] Add user authentication (username/password)
- [ ] Store user data persistently (JSON or SQLite)
- [ ] Support WebSocket connections
- [ ] Create a web-based client
- [ ] Build a GUI client (C# WPF / Avalonia or Go webview)

---

## Phase 4: Hosting & Deployment

- [ ] Containerize the server with Docker
- [ ] Host it on a VPS (e.g., DigitalOcean, Linode)
- [ ] Add logging and monitoring
- [ ] Secure the server (TLS, rate limiting)
- [ ] Write a setup guide for new users

---

## Bonus Ideas

- [ ] Emoji support or command shortcuts
- [ ] Chat rooms or channels (`/join room1`)
- [ ] Rate limiting / flood protection
- [ ] Admin moderation commands (`/kick`, `/ban`)


