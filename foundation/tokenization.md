#### Tokenization & Vocabulary

**Vocabulary**
- Vocabulary = Unique set of tokens in a tokenizer
- Tokens can be:
    - Characters
    - Words
    - Subwords
    - Numbers, code, emojis, etc.

**Encoder & Decoder**
>Encoder → Converts text → integers (tokens → IDs)
>Decoder → Converts integers → text


**Real Tokenization Methods**
Used in LLMs instead of simple splitting:

- BPE (Byte Pair Encoding)
- WordPiece
- SentencePiece

    Why?
    - Handle unknown words
    - Reduce vocabulary size
    - Capture subword patterns

