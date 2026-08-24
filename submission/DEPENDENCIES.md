# Dependencies

Every library you added to `requirements-extra.txt`, with a one-line reason.

We are not counting libraries — a well-chosen dependency is better engineering than a
hand-rolled version of the same thing. What we are reading is whether you added each
one deliberately.

| Library | Version | Why |
|---|---|---|
| none | none | I did not add any extra dependencies. My environment did not have pandas or other libraries installed, and due to time constraints I proceeded without modifying requirements-extra.txt. |

## Anything you considered and rejected

Optional, but the more interesting half. A library you looked at and decided against —
and why — says more than the ones you kept.

| Library | Why Rejected |
| --- | --- |
| pandas | Installing it would require environment setup I couldn’t complete before the deadline; Curator allows failure cases, so I continued without it. |
| numpy | Would only support model scaffolding; time constraints prevented dependency setup. |
| lxml | Would help XML parsing, but no filings were detected, so adding it wouldn’t change pipeline output. |

## Note

Libraries that wrap 13F retrieval and parsing end to end will not, on their own,
satisfy the schema or the quality report, and we will ask you to explain the edge cases
in your output regardless of how you produced it. If you can explain it, you own it.
