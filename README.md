# orion_ai

Tech stack
Next.js
Clerk auth
drizzleORM + neonDB
Stripe
AWS S3

AI Tech stack
PineconeDB
Langchain
OpenAI
Vercel AI SDK

New concepts
Edge runtime
Retrieval augmented generation


1. obtain the pdf
2. split tand segment the pdf
3. vectorise and embed individual documents
4. store tge vectors into pineconedb

-------search-------
5. embed the query
6. query the pineconedb for similar vectors
7. extacr out the metadata
8. feed metadata into openai prompt