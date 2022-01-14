# sch-corpus

A Hmong language corpus derived from the soc.culture.hmong Usenet group.

## Source

The SCH Corpus is based upon most of the posts from the `soc.culture.hmong` or SCH Usenet group from 1996 to 2016. Posts were scraped from `https://soc.culture.hmong.narkive.com/` (which provided web access to SCH posts).

## File Format

The file is formatted in a CONLL-like way. There are two types of lines:

* Tokens, with fields separated by tokens.
  - First field: word or punctuation
  - Second field: elaborate expression annotation (B, I, O)
* Sentence delimiters (blank lines)


