# Suffixal Derivation between Adjectives and Adverbs

**Authors:**

Tsvetana Dimitrova, Valentina Stefanova (Institute for Bulgarian Language, Bulgarian Academy of Sciences)

## Description

The dataset contains derivationally related adjective–adverb pairs, extracted from Princeton WordNet and aligned with the Bulgarian WordNet.

For each pair, the dataset includes:
- the ID of the adverb synset and its English literal(s);
- the ID of the related adjective synset and its English literal(s);
- the corresponding Bulgarian literals, grouped by verification status: *verified*, *not verified*, and *human expert* (added by an expert);
- the semantic classes of the adverb and the adjective.

A Python script applies basic heuristic rules to find formal derivational correspondences between Bulgarian adjectives and adverbs. Each Bulgarian pair is marked `true` if the rules find a formal match and `false` if they do not. This gave 2,489 matches and 639 non-matches.

Experts checked all 3,128 adjective–adverb pairs that are linked by a derivational relation in Princeton WordNet. The derivational and semantic link between the Bulgarian lexical units was confirmed for 1,882 pairs. For the other 1,246 pairs, the adverb or the adjective synset is missing from the Bulgarian WordNet.

## Format

XML

## License

The resource is distributed under the [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) license.

## References

Stefanova, Dimitrova 2017: Stefanova, V., T. Dimitrova. Classification of Adjectives in BulNet: Notes on an Effort. – In: Proceedings of the LDK 2017 Workshops: 1st Workshop on the OntoLex Model (OntoLex-2017), Shared Task on Translation Inference Across Dictionaries & Challenges for Wordnets co-located with 1st Conference on Language, Data and Knowledge (LDK 2017), 1899, CEUR-WS, pp. 188-196. 

Dimitrova, Stefanova 2018: Dimitrova, T., V. Stefanova. Semantic Classification of Adjectives in the Bulgarian Wordnet: Toward a Multiclass Approach. – Etudes Cognitives, 18, pp. 1 – 17.
