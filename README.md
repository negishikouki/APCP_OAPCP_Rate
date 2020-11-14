# APCP_OAPCP_Rate
PCP:PvP CP = (SCP*10)^(3/2)*DPT[PvP]*10^(-4)

where:

10^(-4) is a scale factor

DPT[PvP] = DPT[fast move] * STF[fast move] * ME[fast move] + EPT[fast move] * DPE[charge move] * STF[charge move] * ME[charge move]

STF:Same Type Factor = (SameType ? 1.2 : 1)

ME:Move Effect=1.6^(TypeChart[MoveType, OppositeType1] + TypeChart[MoveType, OppositeType2])

APCP:Average PCP = Σ(PCP[x])*n^(-1)

OAPCP:Opposite APCP = Σ(Opposite PCP[x])*n^(-1)

APCP probably represents average winnability. That is as better as bigger:)

OAPCP probably represents average defeatabilty. That is as better as smaller:(

APCP / OAPCP Rate is a better index for selecting Pokemons to give you an edge in PvP!!

If APCP / OAPCP >= 1.0 then, that pokemon has an edge in PvP.
