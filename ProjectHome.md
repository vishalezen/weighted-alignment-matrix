In statistical machine translation, word alignment plays an important role because word-aligned bilingual corpus proves to be an excellent source of translation knowledge. The estimation of model parameters usually directly depends on word alignment, not only for phrase-based and hierarchical phrase-based models, but also for syntax-based models. Most SMT systems face the problem of "alignment error propagation" as they only use 1-best alignments. In other words, alignment mistakes might lead to translation mistakes. To alleviate this problem, we propose a structure called weighted alignment matrix, which encodes the probability distribution for exponentially many alignments just in a linear space. In addition, we develop new algorithms to extract phrases and hierarchical phrases efficiently from weighted alignment matrices. This toolkit provides the source code for (1) building weighted alignment matrices from a bilingual corpus using GIZA++, (2) extracting phrases, and (3) extracting hierarchical phrases.