# UmaPilot v0.1.15

- Retry game-data reads rejected with code 394 up to two times, after 3 and 6 seconds, when account and session checks pass. Each retry is shown in the Pilot log.
- Keep career starts, claims, skill purchases, and pulls protected from automatic replay. A failed refresh after successful finalization retries only the refresh.
- Keep the saved next trainee and parents visible while recommendations rebuild, with separate planning progress and error details.

Validated with 88 offline backend tests, six loop/guest preview tests, a dashboard browser regression, and a production UI build. No live career was started or claimed during testing.
