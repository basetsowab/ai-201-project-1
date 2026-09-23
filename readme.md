# The Unofficial Guide

## What This Does

The Unofficial Guide is a document-based question-answering system designed to make information easier to find. A user can ask a question, and the system searches through a collection of documents to find information related to that question.

The goal of the project is to provide answers that are based on the documents instead of information outside of the dataset. The system also identifies where the information came from so that users can understand the source of an answer.

## Document Processing

The system processes the provided documents and prepares them so they can be searched. The documents are divided into smaller sections so the system can focus on information that is most relevant to a user's question.

One thing I learned from this project is that the way documents are processed can affect the quality of the information that gets retrieved. If too much information is grouped together, unrelated information may be returned. If sections are too small, important context may be lost.

## Vector Search

The project uses embeddings and a vector store to search through the documents. Instead of only looking for exact matching words, embeddings allow the system to compare the meaning of a user's question with the meaning of information contained in the documents.

This helped me understand how AI applications can search through large amounts of text and find information that is related to what a user is asking.

## Relevance and Grounding

The system uses a relevance gate to check whether the retrieved information is closely related to the user's question before generating an answer.

I think this is an important part of the project because an AI system should not confidently provide an answer when the available documents do not contain enough information. Grounding the response in retrieved documents also makes it easier to determine where an answer came from.

## How I Used AI

I used AI mainly to help me understand unfamiliar concepts and the structure of the project.

I used AI to better understand document processing, embeddings, vector stores, retrieval, and relevance distance. These explanations helped me understand how the different parts of the system work together.

I also used AI while reviewing the project instructions and starter code. It helped me understand the purpose of different parts of the project and what I should focus on while working through the assignment.

Overall, AI was useful as a learning and support tool because it helped explain concepts that I was unfamiliar with and made the project easier for me to understand.
