# fastapi-mongodb-jobboard
We’ll build a single project with FastAPI + MongoDB that covers:

✅ REST APIs with FastAPI

✅ MongoDB basics (CRUD)

✅ Relationships (one-to-one, one-to-many, many-to-many)

✅ Pydantic models & validation

✅ Dependency injection & routing

✅ Authentication (JWT)

✅ Pagination, filtering, indexing

✅ Async with motor (MongoDB async driver)

We’ll make a Mini Job Board app:
Users (signup/login)

Jobs (posted by users)

Applications (users apply to jobs)

This way, we’ll naturally cover relationships:

User → Jobs (One-to-Many)

User → Applications (One-to-Many)

Job ↔ Applications (One-to-Many)
User ↔ Job (via Applications) (Many-to-Many-like)
