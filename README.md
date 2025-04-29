# Biased-Larry
An ai chatbot trained on curated data to be my PR guy.

## data format

Maybe use markdown files to store data to train on? easy to copy and paste from word docs.

## LLMs

Gemini -- has limitations with free api

Langchain -- allows local LLMs, but might be computationally to heavy for hosting for free.

Haystack -- specializes in rag. has free api.

## Embedding

Seems like langchain includes embedding and text chunking functions.

## Server side

Probably just Pythhon

For rendering, probably Flask.

## Hosting

Burn that bridge when we get there

# Architcture stuff

Current thoughts:

* Create a data folder for storing text information for chunking and embedding. Probably does not need a db because the information will probably not be so sizable as to require that.

* Send context to chatbot api, or send query to pretrained local LLM.

* Render responses via Flask.
