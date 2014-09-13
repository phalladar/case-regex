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
    \d+\s+?[Nn]\.?\s?[Ww]\.?(?:\dd)?\s+\d+ - X N.W(.\dd)? Y
    \d+\s+?[Nn]\.?\s?[Ww]\.?(?:\dd)?\s+at\s+\d+ - X N.W.(.\dd)? at Y

# Southwestern Reporter
    (\d+)\s+([Sn]\.?[Ww]\.?(?:\dd)?\.?)\s+(\d+) -- X S.W.(\dd)? Y

# Southern Reporter
    (\d+)\s+([Ss][Oo]\.(?:\s?\dd)?)\s(\d+) -- X So.(\dd)? Y

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

# 