What is TechDoc Translation Agent?

TechDoc Translation Agent is an "Agentic MT system" specialised to output consistent, idiomatic and faithful translations for (but not technically restricted to) XML-documents.

It achieves state-of-the-art performance in these dimensions, using multiple solutions:

 - Consistent

 - It uses advanced proprietary techniques making use of the semantical relationships between segments of a document, so when the LLM is asked to translate something, it's guaranteed to be fed with just the right context it needs to produce a translation which is consistent in language and fits to document context perfectly. 

 - If the customer wishes to have consistency across publications, there's a possibility to query a TM or termbase as well. Ideally, this makes it possible to automate the whole translation pipeline for any customer who wishes that their content should be localised in a continuous unsupervised manner.

 - Idiomatic 

 - By use of carefully prompted frontier LLMs, "translationese" is avoided to the maximum. 

 - The validation mechanism detects any remaining deficiencies, further refining the output where it sees it necessary.

 - Faithful 

 - By always validating each translation made against the source text, translations are verified to be close in meaning to the source segment.

 - The system also employs several programmatic guardrails, ensuring that XML data structure and numbers are correctly transferred to the output.