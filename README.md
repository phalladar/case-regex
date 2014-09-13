# SCOTUS
    (\d+)\s+([Uu]\.\s?[Ss]\.)\,\s+at\s+(\d+) - X U.S., at Y
    (\d+)\s+([Uu]\.?[Ss])\.?\s+(\d+) - X US Y
    (\d+)\s+?([Ll]\.[Ee][Dd]\.(?:\dd\.?)?)\s+?(\d+) - X L.Ed.(\dd)? Y
    (\d+)\s+?([Ss]\.?\s*[Cc][Tt]\.?)\s+(\d+) - X S. Ct. Y
    (\d+)\s+([Uu]\.?[Ss]\.?[Ll]\.?[Ww]\.?)\s+(\d+) -- X U.S.L.W. Y

    Combined SCOTUS: (?:(\d+)\s+([Uu]\.\s?[Ss]\.)\,\s+at\s+(\d+)|(\d+)\s+([Uu]\.?[Ss])\.?\s+(\d+)|(\d+)\s+?([Ll]\.[Ee][Dd]\.(?:\dd\.?)?)\s+?(\d+)|(\d+)\s+?([Ss]\.?\s*[Cc][Tt]\.?)\s+(\d+)|(\d+)\s+([Uu]\.?[Ss]\.?[Ll]\.?[Ww]\.?)\s+(\d+))

# Federal Reporter
    (\d+)\s+([Ff]\.?(?:\s?\dd)?)\s+(\d+) -- X F. Y
    (\d+)\s+([Ff]\.?\s?[Cc][Aa][Ss]\.?)\s+(\d+) - X F.Cas. Y

# Federal Supplement
    (\d+)\s+([Ff]\.?[Ss][Uu][Pp][Pp]\.?)\s+(\d+)

# Atlantic Reporter
    (\d+)\s+([Aa]\.?(?:\s?\dd)?)\s+(\d+) -- X A(.\dd)? Y

# Pacific Reporter
    (\d+)\s+([Pp]\.?(?:\s?\dd)?)\s+(\d+) -- X P.\dd Y

# Northwest Reporter
    (\d+)\s*([Nn]\.?[Ww]\.?(?:\dd)?)\s*(\d+) -- X N.W.(\dd)? Y

# North Eastern Reporter
    (\d+)\s*([Nn]\.?[Ee]\.?(?:\dd)?)\s*(\d+) -- X N.E.(\dd)? Y

# South Western Reporter
    (\d+)\s+([Ss]\.?[Ww]\.?(?:\dd)?\.?)\s+(\d+) -- X S.W.(\dd)? Y

# Southern Reporter
    (\d+)\s+([Ss][Oo]\.(?:\s?\dd)?)\s(\d+) -- X So.(\dd)? Y

# South Eastern Reporter
    (\d+)\s+([Ss]\.?[Ee]\.?(?:\dd)?\.?)\s+(\d+) -- X S.E.(\dd)? Y

# Alabama
    (\d+)\s+([Aa][Ll][Aa]\.?\s*(?:[Aa][Pp][Pp]\.?)?)\s+(\d+) -- X Ala (App)? Y

# Alaska
    (\d+)\s+([Aa]laska(?:\s+[Ff]ed\.?)?)\s+(\d+)

# Arizona
    (\d+)\s+([Aa][Rr][Ii][Zz]\.?\s*(?:[Aa][Pp][Pp]\.?)?)\s+(\d+) -- X Ariz. (App)? Y

# Arkansas
    (\d+)\s+([Aa]rk\.?\s*(?:[Aa]pp\.?)?)\s+(\d+) -- X Ark. (App)? Y

# California
    (\d+)\s+([Cc]al\.?\s?(?:[Aa]pp|[Ss]upp|[Uu]nrep|[Rr]ptr)?\.?\s?(?:[Ss]upp)?\.?\s?(?:\dd)?)\s+(\d+) -- X Cal (App|Supp|Rptr|Unrep)? (\dd)? Y

# Colorado
    (\d+)\s+([Cc][Oo][Ll][Oo]\.?\s*(?:[Aa][Pp][Pp]\.?)?)\s+(\d+) -- X Colo. (App)? Y

# Connecticut
    (\d+)\s+(Conn\.?\s?(?:[Ss]upp|L\.?\s?[Rr]ptr|[Ss]uper(?:\.?\s?[Cc]t)?)?)\.?\s?(\d+) -- X Conn (Supp|LRptr|Super(Ct)?)?

# Delaware
    (\d+)\s([Dd]el\.?\s*(?:[Cc]h|[Cc]as)?\.?)\s*(\d+) -- X Del. (Ch|Cas)? Y

# District of Columbia
    (\d+)\s*([Uu]\.?[Ss]\.?\s*[Aa]pp\.?\s*[Dd]\.?[Cc]\.?)\s*(\d+) -- X U.S. App. D.C. Y
    (\d+)\s*([Aa]pp\.?\s*[Dd]\.?[Cc]\.?)\s*(\d+) -- X App. D.C. Y

# Florida
    (\d+)\s*([Ff]la\.?\s*(?:Supp\.?)?\s*(?:\dd)?)\.?\s*(\d+) -- X Fla. (Supp(\dd)?)? Y 

# Georgia
    (\d+)\s*([Gg]a\.?\s*(?:[Aa]pp)?\.?)\s*(\d+) -- X Ga (App)? Y

# Hawaii
    (\d+)\s*([Hh]aw\.?\s*(?:[Aa]pp)?\.?)\s*(\d+) X Haw (App)? Y

# Idaho
    (\d+)\s*([Ii]daho)\s*(\d+) -- X Idaho Y

# Illinois
    (\d+)\s*([Ii]ll\.?(?:\s*Dec|\s*App)?\.?\s*(?:\dd)?\.?)\s*(\d+) -- X Ill. (Dec|App)? (\dd)? Y

# Indiana
    (\d+)\s*([Ii]nd\.?\s*(?:[Aa]pp)?\.?)\s*(\d+) X Ind. (App)? Y

# Iowa
    (\d+)\s*([Ii]owa)\s*(\d+) -- X Iowa Y

# Kansas
    (\d+)\s*([Kk]an\.?(?:\s*App\.?)?\s*(?:\dd\.?)?)\s*(\d+) - X Kan. (App)? (\dd)? Y