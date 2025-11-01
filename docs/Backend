Backend: Next 9

Tech Stack (Lovable Platform)

Frontend: React + Vite (Single Page Application)
Backend: Lovable's integrated backend
Platform: Mobile-responsive web application

Minimal Data Model

Entity: GridSession

Fields:

sessionId: string - Unique identifier for the current device/session.

coreVibe: string - The descriptive text analyzed from the current reference image.

images: Array<ImageItem> - The current 9 images in the grid.

Entity: ImageItem (Nested within GridSession.images)

Fields:

src: string - Lovable-hosted URL or Base64 data for the generated image.

prompt: string - The text prompt used for image generation.

isSelected: boolean - True if the user has selected/kept this image.

What We're NOT Building

For MVP, no need for:

User accounts or authentication.

Complex database relationships (only one primary entity is required).

Admin interfaces.

Storing or managing user-uploaded raw image files (we assume the AI analysis happens immediately, and the coreVibe is saved).

Implementation Notes

Since Lovable provides full-stack capabilities:

Data storage handled by Lovable's backend.

No need for external services (Supabase, Firebase, etc.).

API endpoints managed within the Lovable platform.
