# sch-corpus

A Hmong language corpus derived from the soc.culture.hmong Usenet group.

## Source

The SCH Corpus is based upon most of the posts from the `soc.culture.hmong` or SCH Usenet group from 1996 to 2016. Posts were scraped from `https://soc.culture.hmong.narkive.com/` (which provides web access to SCH posts). The same content can be accessed via Google Groups and other free Usenet archives.

## Privacy and Intellectual Property

Posts have been anonymized to the degree possible given the available resources. All headers and metadata have been removed from posts. Some personal names, especially of public figures, and user names may remain.

If you are an author of material that is present in this corpus and you believe that the material is being used and or distributed without your consent and contrary to your desires, please contact [David R. Mortensen](mailto:dmortens@cs.cmu.edu) and provide him with the file names where the relevant posts occur. These will be immediately expunged from the corpus.

Unfortunately, we cannot remove posts from the public archives from which this corpus is derived.

## Offensive Content

Because of the spirited, unrestrained, and sometimes acrimonious nature of conversation on SCH, there is a certain amount of offensive content in the corpus, including abusive language and racial, ethnic, gender, and sexual bias. Researchers who train NLP models on the corpus should do so with caution, since such models are likely to reflect the biases and offensive language present within the data. In future work, we plan to annotate the corpus for various types of offensive content as part of a study of abusive language recognition in low-resource languages.

## File Format

The file is formatted in a CONLL-like way. There are two types of lines:

* Tokens, with fields separated by tokens.
  - First field: word or punctuation
  - Second field: elaborate expression labels drawn from the set {B, I, O}
* Sentence delimiters (blank lines)


