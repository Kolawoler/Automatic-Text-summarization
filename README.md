This project primarily focuses on summarizing articles, newsletters, and extensive textual data by highlighting important information within a large corpus. Here's an overview of the project's architecture:

Data Collection: Gather text data from articles through extraction techniques.

Data cleaning: Perform preprocessing tasks such as tokenization, stop word removal, and converting text to lowercase. Additionally, create a dictionary of words based on their occurrence frequency and perform Sentence Tokenization.

Sentence Selection: Select sentences with the highest score to generate a summary using the heapq library.
