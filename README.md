# ChatPDF Clone

A ChatPDF clone using:

- Next.js 13 (App Router) in TypeScript
- Database
  - Drizzle ORM
  - Neon (Serverless PostgreSQL)
- AI-related
  - Pinecone (Vector Database)
  - Langchain
  - OpenAI SDK
  - Vercel AI SDK
- API schema validation: Zod
- Object Storage: AWS JavaScript SDK v2
- Payment: Stripe SDK
- Styling: Tailwind CSS
- Third-Party UI Components
  - React Dropzone
  - React Hot Toast
  - shadcn-ui
  - Lucide icons

## Acknowledgement

This repo is a walkthrough demo based Elliott Chong's video: https://www.youtube.com/watch?v=bZFedu-0emE

However, I made following changes:

- refreshed SDK versions and related code
- dropped usage of React Query due to error, used fetch API instead
- dropped usage of edge runtime for routes due to error running Pinecone SDK
- reorganized some parts of the code
- and many more ...
