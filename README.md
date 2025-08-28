# whosincharge

The repository documents and makes public the work of the University of Chicago's Urban Health Lab and Philomena Kebec of the Bad River Band of Lake Superior Chippewa Indians to assess on which Federally recognized Tribal lands the State has criminal jurisdiction over all crimes.

The goal of this project is to document the extent of state criminal jurisdiction on the trust lands of federally recognized tribes. In practice, this means documenting where the state has criminal jurisdiciton over crimes committed by tribal members against other tribal members. The bulk of this jurisdiction is defined by Public Law 280, but some state laws have the same effect and this authority can also be complicated by retrocessions, federal recognition of Tribes post-1953, and idisynchratic state laws and policies. The goal of this project was
to identify for each tribe-county combination the extent of the state's criminal jurisdiction on tribal lands so that researchers can investiage the public policy impact of different jurisdictional regimes.

*** Variables ***

STATEFP - The State Fips code.

COUNTYFP - The County Fips code.

NAMELSAD - The Name of the County or geographic entity where the Tribal lands reside

AGENCY - The BIA Sub Agency responsible for these Tribal Lands

LARNAME - The name of the Land Area Representation for these specific lands in this
specific county

Tribe Name - The name of the Tribe

State has criminal jurisdiction? - A 0,1 variable where 0 indicates that the state does not have jurisdiction over crimes committed by tribal members against tribal members and 1 indicates that the state has some jurisdiction over crimes committed by tribal members against tribal members.

PL280? - A 0,1 variable indicating if the state is a mandatory public law 280 state.

Retrocession - A 0,1 variable indicating if criminal jurisdiction on this land was retroceded back to the tribe.

Partial Jurisdiction? - A write up of instances where the state has some criminal jurisdiction over crimes committed by tribal members against other tribal members.

notes - Our write up of how this specific tribal land - county dyad was coded

Citations- citations for any sources in the notes section
