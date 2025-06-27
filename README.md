
# Discord Server Admin Dashboard

This is a fully custom-built Discord Server Admin Dashboard built using **Next.js 14 App Router** and **Tailwind CSS**. It includes mocked features like managing members, roles, messages, and viewing server metrics — with full responsiveness and interaction.

# Approach
This project was developed from scratch based on the given task requirements:

- **Next.js 14+ App Router** for routing and layout management.
- **Tailwind CSS** for fast, utility-first styling.
- **Lucide Icons** for modern iconography.
- **React Hooks** for local state management (pagination, filtering, modal toggle, etc.).
- No Redux, Zustand, or external UI libraries used — fully custom UI.
- Mock data used for all sections (no backend or real API calls except for public mock APIs like randomuser.me).

### Pages Implemented:

- **Dashboard**:
  - 5 metric cards: Total Members, Online Users, Messages Today, Active Roles, New Members This Week.
  - Line and bar charts to display member trends (mocked).
- **Members**:
  - Searchable, sortable, and paginated table of users.
  - Avatar, Username, Join Date, Role.
  - Filter by role.
  - Modal to add a new member (mock only).
- **Roles**:
  - List of roles with Tailwind-based color labels.
  - Toggle switches for visibility.
  - Mock input to rename a role.
- **Messages**:
  - List of messages with avatar, username, timestamp, content.
  - Delete button (UI only).

# Getting Started
### 1. Clone the Repository

```bash
git clone https://github.com/HarshalMargaj/discord-server-admin-dashboard.git
cd discord-admin-dashboard

```
### 2. Install Dependencies
```bash
npm install
```
### 3. Run Development Server
```bash
npm run dev
```

# Screenshots
<img width="1440" alt="Screenshot 2025-06-27 at 9 37 46 PM" src="https://github.com/user-attachments/assets/7c5ec366-dc5b-4123-bb92-d00e0b730dc2" />
<img width="1440" alt="Screenshot 2025-06-27 at 9 37 38 PM" src="https://github.com/user-attachments/assets/8effefc6-c597-4aa9-a97b-c513033ebd19" />
<img width="1440" alt="Screenshot 2025-06-27 at 9 37 20 PM" src="https://github.com/user-attachments/assets/d815f816-1ee1-4cb7-b4be-3a127da7361a" />
<img width="1440" alt="Screenshot 2025-06-27 at 9 37 13 PM" src="https://github.com/user-attachments/assets/15633dfd-768f-4958-b1f9-3f7b8b205862" />
<img width="1440" alt="Screenshot 2025-06-27 at 9 37 06 PM" src="https://github.com/user-attachments/assets/43de8f35-4bb4-4a70-9451-cb8654a6f0f6" />
<img width="1440" alt="Screenshot 2025-06-27 at 9 36 57 PM" src="https://github.com/user-attachments/assets/595f18ee-a45a-4782-8807-1da0e7de0237" />
