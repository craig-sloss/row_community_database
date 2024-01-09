# Questions

* Difference between UNIT, VERTICAL_UNIT, HORIZONTAL_UNIT

* Impact of PENDING status

* How have other campaigns managed the DNCL in the past? 

* Can we form an organization to register with the DNCL?

* Ho do we handle cell phones? Assuming directories for addresses give land lines only.

# Observations / conclusions

* In Ward 10, only 21 buildings with 100+ units. Would be reasonable to search these manually.

* Significant number of Ward 10 buildings have only one unit, so this may not be exclusively multi-residential buildings. Is there a way to identify buildings where we don't need special permission to access?

* Could potentially use canada411.ca to do reverse lookup on addresses. If we can do this in an automated way, it's ideal; otherwise we could manually look up some of the largest buildings. Example: https://www.canada411.ca/search/?stype=ad&st=55+duke&ci=kitchener&pv=ON&pc=

** URL name changes on the "Next" page but still appears to have a pattern to it, e.g. here is the link to the fourth page: https://www.canada411.ca/search/ad/4/-/cZQQstZ55+dukeQQciZkitchenerQQpvZONQQpcZ/

* This page appears to sell a full database of white pages data, but it costs \$1000 for rights to merge data, \$2000 for full ownership: https://www.odditysoftware.com/page-datasales778.htm

# Potential future work

* Plot concentrations of buildings on a map

# Recommendations

1. Manual search for property management / superintendents in largest buildings. Combination of Google, Condo Authority Ontario, Property Ownership database. Optional: purchase smartscraper for $79 to get all property managers; it will give their office but not necessarily the building they manage.

2. For individual addresses, set up an automated scrape of Canada 411. If that doesn't work, do it manually for the largest buildings.

3. To access the DNCL, we need to register as an organization (30 days lead time) and then request via e-mail to the DNCL, and get an API key.

