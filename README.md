# Predictive Contracts

This project involves steps for working with predictive contracting by extracting, embedding, and mapping opcodes to enable advanced contract analytics. Also meant for the development of "predictive contracts", which are a way for smart contracts to adapt over time to new situations

---

### Steps Summary

1. **Extract Opcodes from Original File Folder** [optional]
2. **Extract Multiple Opcodes and IDs** [Compulsory]
3. **Develop Text Opcodes** for the generated Multiple Opcodes and Text IDs.
4. **Build Vocabulary** for the generated Opcodes and IDs.
5. **Generate Word2Vec Embeddings** from the vocabulary (optionally converting it to a text file).
6. **Embed Opcodes** using the generated Word2Vec embeddings.
7. **Embedding Completed**: Once embedded, we have two folders:
   - **With ID**
   - **Without ID**
8. **Convert to Text Files**
9. **Build Relationships**: Develop relationships between opcodes and embeds using paths.
10. **Implement Checker Code**: This includes two implementations.

---

### File Paths

The original files and various generated files are organized as follows:

#### Original File:
- **Original Compiled Contract**: [ORIGINALFLOOR](https://drive.google.com/drive/folders/1H7J_6TlkLg5-SjRfUgYX6xN1JQHMDsKS?usp=sharing)

#### Extracted Opcodes and Associated Files

1. **Predict 1**
   - First Original Compiled Contract - F1(A): [PREDICT1](https://drive.google.com/drive/folders/1TbO6kjLQUI24W5abRyS7XZ01ogCUFt90?usp=sharing)
   - Opcodes: [predictoneopecodes](https://drive.google.com/drive/folders/1UGC6yDOLqjYxWyY8gdZzUV4M7R5zCpOW?usp=sharing)
   - Opcode Text Corpus: [opcodes_one_corpus.txt](https://drive.google.com/file/d/1j7tl_kxiaKwVL6QmJnRJZiDrUQrg5Vb-/view?usp=sharing)
   - Vocabulary: [firstvocabularybuildfolder2](https://drive.google.com/drive/folders/1jKpnZz1J6tZpvJtmg2hEONtVSJxrt4_T?usp=sharing)
   - Word Vectors: [firstmyword_vectors.txt](https://drive.google.com/file/d/1jp3poWY5XuEpEYDT_s-g71fLTnSGMfx8/view?usp=sharing)
   - Vocabulary as Text: [firstmyvocabulary.txt](https://drive.google.com/file/d/1jq9dMv6w0xQMQl-5n_9KIu7PUSH3RIXL/view?usp=sharing)
   - Embedded File: [firstmynewembeds](https://drive.google.com/drive/folders/1Ij3CxdE0vOMTnbSQbKOOVXjPEvPzhhG-?usp=sharing)

2. **Predict 2**
   - Second Original Compiled Contract - F1(B): [PREDICT2](https://drive.google.com/drive/folders/1DUaTKtJhVJ0hDIuj2AW8ESCQvJFx1bY-?usp=sharing)
   - Opcodes: [predicttwoopcodes](https://drive.google.com/drive/folders/1EqSuKZFTBQ_9wyG1Mf0lu6gfB9AstEfH?usp=sharing)
   - Opcode Text Corpus: [opcodes_two_corpus.txt](https://drive.google.com/file/d/1j7vJfnQ4LdRWzMdfn__kpJqkycxYIzgH/view?usp=sharing)
   - Vocabulary: [secondvocabularybuildfolder2](https://drive.google.com/drive/folders/1jVApMoFeRKtwD-XxrMVIh-FJZbKzjkhu?usp=sharing)
   - Word Vectors: [secondmyword_vectors.txt](https://drive.google.com/file/d/1jup2-gD4yklLmCcdPE5IuSc7f-Pm8j8y/view?usp=sharing)
   - Vocabulary as Text: [secondmyvocabulary.txt](https://drive.google.com/file/d/1k35ZPBXNgt1Mi6RWfFOPTVuy7fp5oRUy/view?usp=sharing)
   - Embedded File: [secondmynewembeds](https://drive.google.com/drive/folders/177s6e_-Q7Xu6nY3zXJCWXfHt8KnGbd2h?usp=sharing)

3. **Predict 3**
   - Third Original Compiled Contract - F1(C): [PREDICT3](https://drive.google.com/drive/folders/1pR2iuXn2UZ8yq851Hwr7oxLmL_yzW8TN?usp=sharing)
   - Opcodes: [predictthreeopcodes](https://drive.google.com/drive/folders/1YsuCgYeXNty3_ryxgMHeyIoDYW7sfKok?usp=sharing)
   - Opcode Text Corpus: [opcodes_three_corpus.txt](https://drive.google.com/file/d/1j9HbhAc_e_D82uzirMccftegULBw24Q7/view?usp=sharing)
   - Vocabulary: [thirdvocabularybuildfolder2](https://drive.google.com/drive/folders/1jmCIRhZoeJRwmfTgilaPZz-pg9eSz08C?usp=sharing)
   - Word Vectors: [thirdmyword_vectors.txt](https://drive.google.com/file/d/1k78oieMCPOwZ_NtJ6Ay3BScgZJixxmgG/view?usp=sharing)
   - Vocabulary as Text: [thirdmyvocabulary.txt](https://drive.google.com/file/d/1k7Ta2cHfwi9ql1A4ZDIoUx681M0CwHI-/view?usp=sharing)
   - Embedded File: [thirdmynewembeds](https://drive.google.com/drive/folders/1FMQsl3bOFyxR8qsv6xnJ4LKLcwo9rRie?usp=sharing)

---

### Continued Process

1. **Code for Continued Scenarios**: We have two folders:
   - **Opcodes with ID**
   - **Opcodes without ID**

2. **Embed Both Folders**: Creating two additional folders:
   - **Embedded code with ID**
   - **Embedded code without ID**

3. **Convert Embedded Files to Text**

4. **Map Paths**:
   - **No ID Opcodes to Embedded Files** (Mapping by path).
   - **ID Opcodes to Embedded Files** (Mapping by path).

5. **Dynamic and Static Parts Identification**: Implemented in:
   - **Implementation 1**
   - **Implementation 2**

### Note:
If the original files change, this implementation should detect these changes.
