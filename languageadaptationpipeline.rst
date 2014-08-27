The Language Resource Adaptation Pipeline implements a methodology for legacy language resource adaptation that generates domain-specific sentiment lexicons organized around domain entities described with lexical information and sentiment words described in the context of these entities. 

method generates domain-specific sentiment lexicons from legacy language resources and enriching them with semantics and additional linguistic information from re- sources like DBpedia and BabelNet. The language re- sources adaptation pipeline consists of four main steps highlighted by dashed rectangles in Figure 1: (i) the Cor- pus Conversion step normalizes the different language re- sources to a common schema based on Marl and NIF4; (ii) the Semantic Analysis step extracts the domain-specific entity classes and named entities and identifies links be- tween these entities and concepts from the LLOD Cloud; (iii) the Sentiment Analysis step extracts contextual senti- ments and identifies SentiWordNet synsets corresponding to these contextual sentiment words; (iv) the Lexicon Gen- erator step uses the results of the previous steps, enhances them with multilingual and morphosyntactic information and converts the results into a lexicon based on the lemon and Marl formats. Different language resources are pro- cessed with variations of the given adaptation pipeline. 