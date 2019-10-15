# ranking-aggregation

ranking(pmat,max_iter=100000)

pmat is an n by n preference matrix for all pairwised objects.
if there's no knowledge about the preference between two objects,
you're suggested to set both correspondings cells to 0.5 (assuming
you normalize the preference).
If you believe there should be an anther and the func raise an
error saying cannot converge, increase max_iter to a lager number.
