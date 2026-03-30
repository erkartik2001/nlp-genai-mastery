# Core terminology (Foundation Layer)

### What is NLP

#### Natural Language Processing (NLP) is the field of AI that enables machines to understand, interpret, generate and manipulate human language.

#### It Combines:

- Linguistics
- Statistics
- Machine Learning
- Deep Learning

---

### What is Text?

#### In NLP text is treated as:

- A sequence of tokens
- A probablity distribution over vocabulary
- A structured signal with syntax + semantics

---

### What is a Language Model?

#### A language model estimates: P(w<sub>1</sub>, w<sub>2</sub>, w<sub>3</sub>...w<sub>n</sub>)

#### Meaning - The probablity of a sequence of words.

#### LLMs are just very advance language models.

---

### What is Tokenization?

#### Breaking text into units:

- Words
- Subwords
- Characters

#### Example: "Playing" -> ["Play", "##ing"] (WordPiece) 
#### This is extremly important foir transformers.

---

### What is Embedding?

#### Mapping discrete tokens into continuous vector space.

#### "king" -> [0.12, -0.44, 0.91, ...]
#### Vectors encode meaning relationships