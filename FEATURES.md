# FlashTalk: Features

## Problem Statement
Students and club members on a campus rely on scattered WhatsApp groups
and email threads to coordinate, which makes conversations hard to organise,
search or revisit. FlashTalk is a real-time chat app where users sign up,
join topic-based rooms for their club or class, and talk instantly, with
saved message history, online presence and typing indicators.

## User Roles
- **Guest**: can only view the login and signup pages
- **Member**: a logged-in user who can join rooms, chat, and edit their profile
- **Room Owner**: a member who created a room; can edit or delete it

## MVP (must-haves)
1. Signup with validation and hashed passwords
2. Login with JWT authentication
3. Create a room
4. Browse, search and join rooms
5. Edit and delete a room (owner only)
6. Send and receive messages in real time (Socket.io)
7. Message history saved in MongoDB and loaded on joining a room
8. Online users list per room
9. Typing indicator
10. Basic profile with name and avatar

## Later (post-MVP)
- Private direct messages
- Message edit and delete
- Emoji reactions
- Image and file sharing
- Read receipts and unread counts
- Message search
- Private rooms with invite links
- Admin moderation tools
- Push notifications
- Dark mode
