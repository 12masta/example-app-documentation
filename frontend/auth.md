# Frontend auth

Sign-in stores a JWT from the backend and restores the session on reload. The current user is available to page loaders through a user context. Unauthenticated visitors can read the global feed and articles. Personal feed, editor, settings, follow, and favorite require a session.
