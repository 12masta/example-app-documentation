# Backend architecture

The API is an ASP.NET service with REST routes for users, profiles, articles, comments, tags, and favorites. JSON payloads follow the Conduit contract the generated frontend client expects. Persistence and auth sit behind the HTTP layer. Hub Functions do not run this API.
