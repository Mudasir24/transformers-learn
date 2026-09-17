# Transformers Learn

A hands-on journey to understand **Transformers from first principles** — studying the concepts, working through the mathematics, and implementing them in code.

---

## 📚 Learning Progress

### Day 1 — Self-Attention

* Studied Self-Attention from the book and handwritten notes
* Worked through the underlying concepts and mathematics
* Implemented Simple Self-Attention from scratch in code


### Day 2 — Self-Attention: Q, K, V

* Implemented Query, Key, and Value vectors from scratch
* Calculated attention scores using Query–Key dot products
* Applied scaling and softmax to obtain attention weights
* Calculated context vectors as weighted sums of Values
* Wrapped the complete self-attention mechanism into a PyTorch class
* Implemented a second version using `nn.Linear` with optional bias


### Day 3 — Causal Attention

* Implemented Causal Attention from scratch
* Applied causal masking to prevent tokens from attending to future tokens
* Calculated masked attention scores and attention weights
* Generated context vectors using the masked attention weights


### Day 4 — Multi-Head Attention

* Implemented Multi-Head Attention using multiple Causal Attention heads
* Created a batch of input sequences
* Combined the outputs from multiple attention heads
* Verified the resulting context vector dimensions


### Day 5 — Multi-Head Attention

* Implemented Multi-Head Attention with weight splitting
* Split Query, Key, and Value projections into multiple heads
* Applied causal masking and scaled softmax attention independently across heads
* Calculated context vectors for each attention head
* Concatenated the outputs from all heads
* Implemented the complete Multi-Head Attention mechanism as a PyTorch class
* Added an output projection layer to combine the concatenated head outputs


---

> 🚧 This is a learning-in-public repository. Notes, implementations, experiments, and understanding will be added as I progress.


## 🤝 Join In

If you're learning Transformers too, feel free to **follow along, open an Issue, or start a Discussion**. I'd be happy to learn together and exchange ideas.
