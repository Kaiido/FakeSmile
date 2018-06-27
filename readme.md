### Fork of well known [FakeSmile](https://github.com/FakeSmile/FakeSmile) library
#### Intended to quick-fix their broken-in-MSEdge feature detection.
(See https://github.com/FakeSmile/FakeSmile/issues/7)

This fork applies the workaround described in https://github.com/FakeSmile/FakeSmile/issues/7#issuecomment-223780635 with the improvement described in https://github.com/FakeSmile/FakeSmile/issues/7#issuecomment-311973295

Uses the modernizr detection.  
`smilanimns`, `smil2ns`, `smil21ns` and `smil3ns` are still incorrectly marked as supported, but these seem to be for external SMIL documents, rather rare on the Internets.

This workaround should already enable basic inline SMIL in SVG.