# learning-the-law
This repository provides some early-stage work on machine learning and the Supreme Court. In particular, it operationalizes a model for legal reasoning in the Supreme Court by classifying Supreme Court opinions into factfinding, law-declaring, and law-applying functions.

The data used in the juptyer notebook come from the website courtlistener.com. Anyone can freely access this data by creating a free account, obtaining an API key, and using the following URL query: https://www.courtlistener.com/api/rest/v4/opinions/?cluster__docket__court=scotus&cluster__date_filed__gte=2005-09-29&type=010combined.
