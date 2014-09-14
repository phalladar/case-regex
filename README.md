# SCOTUS
    (\d+)\s*([Uu]\.\s?[Ss]\.)\,\s*at\s*(\d+) — X U.S., at Y
    (\d+)\s*([Uu]\.?[Ss])\.?\s*(\d+) — X US Y
    (\d+)\s*?([Ll]\.[Ee][Dd]\.(?:\dd\.?)?)\s*?(\d+) — X L.Ed.(\dd)? Y
    (\d+)\s*?([Ss]\.?\s*[Cc][Tt]\.?)\s*(\d+) — X S. Ct. Y
    (\d+)\s*([Uu]\.?[Ss]\.?[Ll]\.?[Ww]\.?)\s*(\d+) — X U.S.L.W. Y

    Combined SCOTUS: (?:(\d+)\s*([Uu]\.\s?[Ss]\.)\,\s*at\s*(\d+)|(\d+)\s*([Uu]\.?[Ss])\.?\s*(\d+)|(\d+)\s*?([Ll]\.[Ee][Dd]\.(?:\dd\.?)?)\s*?(\d+)|(\d+)\s*?([Ss]\.?\s*[Cc][Tt]\.?)\s*(\d+)|(\d+)\s*([Uu]\.?[Ss]\.?[Ll]\.?[Ww]\.?)\s*(\d+))

# Federal Reporter
    (\d+)\s*([Ff]\.?(?:\s?\dd)?)\s*(\d+) — X F. Y
    (\d+)\s*([Ff]\.?\s?[Cc][Aa][Ss]\.?)\s*(\d+) — X F.Cas. Y

# Federal Supplement
    (\d+)\s*([Ff]\.?\s*[Ss][Uu][Pp][Pp]\.?)\s*(\d+)

# Atlantic Reporter
    (\d+)\s*([Aa]\.?\s*(?:\s?\dd)?)\s*(\d+) — X A(.\dd)? Y

# Pacific Reporter
    (\d+)\s*([Pp]\.?\s*(?:\s?\dd)?)\s*(\d+) — X P.\dd Y

# Northwest Reporter
    (\d+)\s*([Nn]\.?\s*[Ww]\.?\s*(?:\dd)?)\s*(\d+) — X N.W.(\dd)? Y

# North Eastern Reporter
    (\d+)\s*([Nn]\.?\s*[Ee]\.?\s*(?:\dd)?)\s*(\d+) — X N.E.(\dd)? Y

# South Western Reporter
    (\d+)\s*([Ss]\.?\s*[Ww]\.?\s*(?:\dd)?\.?)\s*(\d+) — X S.W.(\dd)? Y

# Southern Reporter
    (\d+)\s*([Ss][Oo]\.\s*(?:\s?\dd)?)\s*(\d+) — X So.(\dd)? Y

# South Eastern Reporter
    (\d+)\s*([Ss]\.?\s*[Ee]\.?\s*(?:\dd)?\.?)\s*(\d+) — X S.E.(\dd)? Y

# Alabama
    (\d+)\s*([Aa][Ll][Aa]\.?\s*(?:[Aa][Pp][Pp]\.?)?)\s*(\d+) — X Ala ([Aa]pp)? Y

# Alaska
    (\d+)\s*([Aa]laska(?:\s*[Ff]ed\.?)?)\s*(\d+)

# Arizona
    (\d+)\s*([Aa][Rr][Ii][Zz]\.?\s*(?:[Aa][Pp][Pp]\.?)?)\s*(\d+) — X Ariz. ([Aa]pp)? Y

# Arkansas
    (\d+)\s*([Aa]rk\.?\s*(?:[Aa]pp\.?)?)\s*(\d+) — X Ark. ([Aa]pp)? Y

# California
    (\d+)\s*([Cc]al\.?\s?(?:[Aa]pp|[Ss]upp|[Uu]nrep|[Rr]ptr)?\.?\s?(?:[Ss]upp)?\.?\s?(?:\dd)?)\s*(\d+) — X Cal ([Aa]pp|Supp|Rptr|Unrep)? (\dd)? Y

# Colorado
    (\d+)\s*([Cc][Oo][Ll][Oo]\.?\s*(?:[Aa][Pp][Pp]\.?)?)\s*(\d+) — X Colo. ([Aa]pp)? Y

# Connecticut
    (\d+)\s*(Conn\.?\s?(?:[Ss]upp|L\.?\s?[Rr]ptr|[Ss]uper(?:\.?\s?[Cc]t)?)?)\.?\s?(\d+) — X Conn (Supp|LRptr|Super(Ct)?)?

# Delaware
    (\d+)\s([Dd]el\.?\s*(?:[Cc]h|[Cc]as)?\.?)\s*(\d+) — X Del. (Ch|Cas)? Y

# District of Columbia
    (\d+)\s*([Uu]\.?[Ss]\.?\s*[Aa]pp\.?\s*[Dd]\.?[Cc]\.?)\s*(\d+) — X U.S. [Aa]pp. D.C. Y
    (\d+)\s*([Aa]pp\.?\s*[Dd]\.?[Cc]\.?)\s*(\d+) — X [Aa]pp. D.C. Y

# Florida
    (\d+)\s*([Ff]la\.?\s*(?:Supp\.?)?\s*(?:\dd)?)\.?\s*(\d+) — X Fla. (Supp(\dd)?)? Y 

# Georgia
    (\d+)\s*([Gg]a\.?\s*(?:[Aa]pp)?\.?)\s*(\d+) — X Ga ([Aa]pp)? Y

# Hawaii
    (\d+)\s*([Hh]aw\.?\s*(?:[Aa]pp)?\.?)\s*(\d+) — X Haw ([Aa]pp)? Y

# Idaho
    (\d+)\s*([Ii]daho)\s*(\d+) — X Idaho Y

# Illinois
    (\d+)\s*([Ii]ll\.?(?:\s*Dec|\s*[Aa]pp)?\.?\s*(?:\dd)?\.?)\s*(\d+) — X Ill. (Dec|[Aa]pp)? (\dd)? Y

# Indiana
    (\d+)\s*([Ii]nd\.?\s*(?:[Aa]pp)?\.?)\s*(\d+) — X Ind. ([Aa]pp)? Y

# Iowa
    (\d+)\s*([Ii]owa)\s*(\d+) — X Iowa Y

# Kansas
    (\d+)\s*([Kk]an\.?(?:\s*[Aa]pp\.?)?\s*(?:\dd\.?)?)\s*(\d+) - X Kan. ([Aa]pp)? (\dd)? Y

# Kentucky
    (\d+)\s*([Kk]y\.?\s*(?:[Aa]pp)?\.?)\s*(\d+) — X Ky. ([Aa]pp)? Y

# Louisiana
    (\d+)\s*([Ll]a\.?(?:\s*(?:[Aa]pp|[Aa]nn)?\.?)?\s*(?:\dd\.?)?)\s*(\d+)

# Maine
    (\d+)\s*([Mm]e\.?\.?\s*(?:\dd)?\.?)\s*(\d+)

# Maryland
    (\d+)\s*([Mm]d\.?(?:\s*[Aa]pp\.?)?\s*(?:\dd\.?)?)\s*(\d+)

# Massachusetts
    (\d+)\s*([Mm]ass\.?\s*(?:[Ss]upp\.?)?\s*(?:[Aa]pp\.?)?\s*(?:[Cc]t|[Dd]iv|[Dd]ec)?\.?)\s*(\d+)

# Michigan
    (\d+)\s*([Mm]ich\.?(?:\s*[Aa]pp\.?)?\s*(?:\dd\.?)?)\s*(\d+)

# Minnessota
    (\d+)\s*([Mm]inn\.?(?:\s*[Aa]pp\.?)?\s*(?:\dd\.?)?)\s*(\d+)

# Mississippi
    (\d+)\s*([Mm]iss\.?\s*(?:[Dd]ec\.?)?)\s*(\d+)

# Missouri
    (\d+)\s*([Mm]o\.?(?:\s*[Aa]pp\.?)?\s*(?:\dd\.?)?)\s*(\d+)

# Montana
    (\d+)\s*([Mm]ont\.?(?:\s*[Aa]pp\.?)?\s*(?:\dd\.?)?)\s*(\d+) — X Mont. ([Aa]pp)? (\dd)? Y
    (\d+)\s*([Ss]tate\s*[Rr]ptr\.?)\s*(\d+) — X State Rptr. Y

# Nebraska
    (\d+)\s*([Nn]eb\.?(?:\s*[Aa]pp\.?)?\s*(?:\dd\.?)?)\s*(\d+)

# Nevada
    (\d+)\s*([Nn]ev\.?(?:\s*[Aa]pp\.?)?\s*(?:\dd\.?)?)\s*(\d+)

# New Hampshire
    (\d+)\s*([Nn]\.?\s*[Hh]\.?(?:\s*[Aa]pp\.?)?\s*(?:\dd\.?)?)\s*(\d+)

# New Jersey
    (\d+)\s*([Nn]\.?\s*[Jj]\.?\s*(?:[Ss]uper|[Ll]|[Ee]q|[Mm]isc|[Tt]ax)?)\.?\s*(\d+)

# New Mexico
    (\d+)\s*([Nn]\.?\s*[Mm]\.)\s*(\d+)

# New York
    (\d+)\s*([Nn]\.?\s*[Yy]\.?\s*(?:[Ss]up|[Ss]|[Cc]h|[Aa]pp|[Gg]en|[Cc]t|[Cc]iv|[Cc]rim|[Ff]am)?\.?\s*(?:[Cc]t|[Dd]iv|[Tt]erm|[Cc]l)?\.?\s*(?:\dd)?\.?)\s*(\d+)

# North Carolina
    (\d+)\s*([Nn]\.?[Cc]\.?\s*(?:\s*[Aa]pp\.?)?\s*(?:\dd\.?)?)\s*(\d+)

# North Dakota
    (\d+)\s*(?:([Nn]\.?[Dd]\.?|[Dd]akota)\s*(?:\s*[Aa]pp\.?)?\s*(?:\dd\.?)?)\s*(\d+)

# Ohio
    (\d+)\s*([Oo]hio\s*(?:[Ss]t|[Mm]isc|[Cc]t|[Aa]pp|[Cc]\.?[Cc])?\.?\s*(?:[Aa]pp)?\.?\s*(?:\dd)?\.?)\s*(\d+)

# Oklahoma
    (\d+)\s*([Oo]kla\.?(?:\s*[Cc]rim)?\.?\s*(?:\dd\.?)?)\s*(\d+)

# Oregon
    (\d+)\s*([O]\.?[Rr]\.?\s*(?:\s*[Aa]pp\.?|\s*[Tt]ax\.?)?\s*(?:\dd\.?)?)\s*(\d+)

# Pennsylvania
    (\d+)\s*([Pp]\.?[Aa]\.?\s*(?:[Ss]uper|[Cc]ommw|[Dd]\.?\s*\&\s*[Cc]\.?|[Dd]|[Cc])?\.?\s*(?:[Cc]t)?\.?\s*(?:\dd)?\.?)\s*(\d+)

# Rhode Island
    (\d+)\s*([Rr]\.?[Ii]\.?\s*(?:\dd)?)\.?\s*(\d+)

# South Carolina
    (\d+)\s*([Ss]\.?[Cc]\.?\s*(?:\dd)?)\.?\s*(\d+)

# South Dakota
    (\d+)\s*((?:[Dd]akota|[Ss]\.?[Dd]\.?)\s*(?:\dd)?\.?)\s*(\d+)

# Tennessee
    (\d+)\s*([Tt]enn\.?\s*(?:[Cc]rim)?\.?\s*(?:[Aa]pp)?\.?\s*(?:\dd)?\.?\s*)(\d+)