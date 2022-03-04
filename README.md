# GrepBiasIR in CSV
Here you find the dataset adapted for automatic processing.
The formatted version is comprised of eight .csv files: one with all queries and seven with respective documents corresponding to the seven query categories.

## File Format
**queries.csv:**
* `q_id` - unique ID of the query
* `category` - query category (one of seven)
* `query` - query text

**queries-documents_[CATEGORY].csv:**

[CATEGORY] - one of the seven query categories
* `q_id` - unique ID of the query
* `d_id` - unique ID of the document
* `relevant` - document to query relevance judgement (1 - relevant, 0 - not relevant)
* `query` - query text
* `doc_title` - title of the document
* `document` - text of the document
* `content_gender` - gender indication inferred from the text of the document (F - female, M - male, N - neutral)
* `exp_stereotype` - expected stereotype annotation
