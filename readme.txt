Stored XSS zabranime tak ze v gruyere.py budeme v _DoNewsnippet2() kontrolovat zda-li se v pridanem snipetu nenachazi nechteny kod

Reflected XSS zabranime tak ze v gruyere.py budeme v _SendRedirect() kontrolovat zda-li se tam nenachazi nechteny kod

XSRF zabranime pouzitim CSRF tokenu 