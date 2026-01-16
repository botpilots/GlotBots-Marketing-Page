Why does LLMs deliver greater MT quality than NMT?

Unlike NMT models, LLMs are trained to follow general instructions rather than perform translation alone. This allows them to adapt dynamically to the specific requirements of each translation task.

This inherent flexibility of LLMs makes them superior to NMT in several ways.

‣ No Fine-Tuning Required: LLM translations have no need of fine-tuning to deliver bespoke translations. This enables customers just starting out to get custom SOTA quality at a low cost and fast delivery, as either ML engineering nor huge curated datasets are needed.
‣ Unlimited Language Flexibility: LLMs can accept any target language, including dialects and variations, e.g. Canadian French and Swiss German. Furthermore, there's no limit on domain specificity, e.g. "Patent Law Spanish" becomes just as valid as a target language as "es-ES".
‣ More Robust Translations: As LLMs are always informed on context (if used with a good Agentic MT System), they make fewer assumptions and thus less fidelity errors than NMT.
‣ Deeper Semantic Understanding: Because LLMs are trained on orders of magnitude more data than NMT, they interpret meaning more deeply and translate with far greater idiomatic sensitivity. 
‣ Multi-modal Support: LLMs can digest not only text as context, but also images. Inclusion of images (e.g technical illustrations) enhances fidelity further in MT. 
‣ Unlocking New Domains: This enables use of machine translation in new domains where NMT falls short, such as gaming, marketing and literature.

Sadly, many MT vendors out there are not making use of these benefits; they say "we do LLM-based translation" while just exchanging the NMT API with a LLM API, thinking they now have achieved state-of-the-art translations. 

But creating quality translations with LLMs requires a whole system, a so called Agentic MT System.

To make full use of the context window of LLMs, it needs to include many different things, such as specific domain context, previous translations, glossary and specific instructions. These prompt components are dynamically generated for each segment translated. 

To ensure intended outcomes, testing and calibration should always be done during development using data from the agent’s intended domain.

Only when this is done, it gives the LLM the necessary preconditions to realise its full strength as a machine translator, producing output that is both high-quality and reliable—far beyond in cost effectiveness of what any NMT system can achieve.