# How Reliable Is Learned Cardinality Estimation? A Data Model-Centric Analysis and Empirical Study

Shuxun Zhang and Jiaheng Lu, Department of Computer Science, University of Helsinki

ADMA 2026, Special Session on Responsible Data Intelligence (full paper)

## Materials

- [Paper (Author Accepted Manuscript, PDF)](paper/How%20Reliable%20Is%20Learned%20Cardinality%20Estimation%20-%20Author%20Accepted%20Manuscript.pdf)
- [Poster (PDF)](poster/ADMA2026_poster.pdf)

The final version will be published by Springer in the ADMA 2026 proceedings; the DOI will be added here.

## Abstract

Learning-based cardinality estimation (CE) has emerged as a promising alternative to statistics-based techniques. Yet its reliability remains an open question: directional bias, upper-tail risk, and degradation under data or workload shifts.
Existing works typically organize learned CE by learning paradigm, such as query-driven versus data-driven, which can obscure how the underlying data model constrains estimator design and reliability.
We adopt a data model-centric perspective, introducing a unified analytical framework spanning query encoding, data feature extraction, and model adaptation. 
We argue that the most informative classification axis shifts across data models: primary modeling target for relational CE, topology-handling strategy for graph CE, and cross-model integration strategy for multi-model CE.
A relational case study grounds this analysis: a topmost-join probe of PostgreSQL reveals systematic underestimation; a five-seed evaluation with checkpoint reuse across workloads characterizes MSCN's workload-shift degradation; and a matched JOB-light comparison shows that learned estimation can substantially reduce, but does not eliminate, typical and tail errors.
We further assess what current benchmarks reveal about reliability and identify open challenges toward robust, transparent, and reliable cardinality estimation.

**Keywords:** Cardinality Estimation, Learned Query Optimization, Multi-Model Databases, Reliability

## Citation

```bibtex
@inproceedings{zhang2026reliable,
  title     = {How Reliable Is Learned Cardinality Estimation? A Data Model-Centric Analysis and Empirical Study},
  author    = {Zhang, Shuxun and Lu, Jiaheng},
  booktitle = {Advanced Data Mining and Applications (ADMA 2026)},
  year      = {2026},
  publisher = {Springer},
  note      = {Pages and DOI to be added}
}
```

## Contact

shuxun.zhang@helsinki.fi
