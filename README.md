# doc-icecube-ibas-dashboard

https://redmine.astro.unige.ch/issues/23619
https://www.isdc.unige.ch/integral/ibas/cgi-bin/ibas_acs_web.cgi/?trigger=2021-02-13T18-42-11.7184-25313-15248-0

It's a positive experience for several reasons:

* IBAS ACS triggered on the "counterpart" (it has these various dead-time periods due to telemetry sync issues). Having an IBAS trigger within 120s of  a given time is quite rare.
* dashboard showed it, and found the same ACS counterpart IBAS detected independently, and assigned FAP 0.02 . Surely the selection of dashboard counterparts is different, and could be more or less sensitive than IBAS: in terms of FAP, not S/N - in S/N dashboard is much more sensitive than independent IBAS detections. Also it searches only +-300 s which is not too much.
but generally beyond 300s FAP is almost always going to be low, except for really bright GRBs.
* IceCube event was retracted, supporting that FAP of 0.02 is reliable, and it is better to use consistent results from dashboard if unsure
* also dashboard and the workflows are operating just fine for many months without interventions

