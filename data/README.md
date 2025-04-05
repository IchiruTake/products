The collection of data crawling. 

MemoryZone data
- `memoryzone.jsonl`: 
  - Number of Products: 1090
  - Language: Vietnamese (primary) and English
  - Crawling Time: March 24th 2025 -> March 26th 2025
  - Format: JSONL (each line is a JSON)
  - Note: The product's data was analyzed to prevent encoding error. 
- `memoryzone_query_1090_products.txt`
  - Description: The simple Vietnamese document of product specification for RAG study (maximum 200 words per product)
  - How to: I use Gemma-3-12B-it model with custom inference configuration on RTX 4060Ti 16GB to generate document with fixed format template. I myself manually curated all the document to ensure no text error and minimizing un-necessary description based on my expertise, whilst maintaining the writing style of the AI
  - Generation Time: 15 second per product (~ 5h)

- 
