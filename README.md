# SCOTUS
    (\d+)\s+([Uu]\.\s?[Ss]\.)\,\s+at\s+(\d+) - X U.S., at Y
    (\d+)\s+([Uu]\.?[Ss])\.?\s+(\d+) - X US Y
    (\d+)\s+?([Ll]\.[Ee][Dd]\.(?:\dd\.?)?)\s+?(\d+) - X L.Ed.(\dd)? Y
    (\d+)\s+?([Ss]\.?\s*[Cc][Tt]\.?)\s+(\d+) - X S. Ct. Y
    (\d+)\s+([Uu]\.?[Ss]\.?[Ll]\.?[Ww]\.?)\s+(\d+) -- X U.S.L.W. Y

    Combined: (?:(\d+)\s+([Uu]\.\s?[Ss]\.)\,\s+at\s+(\d+)|(\d+)\s+([Uu]\.?[Ss])\.?\s+(\d+)|(\d+)\s+?([Ll]\.[Ee][Dd]\.(?:\dd\.?)?)\s+?(\d+)|(\d+)\s+?([Ss]\.?\s*[Cc][Tt]\.?)\s+(\d+)|(\d+)\s+([Uu]\.?[Ss]\.?[Ll]\.?[Ww]\.?)\s+(\d+))

# Federal Reporter
    \d+\s+[Ff]\.\s+\d+ -- X F. Y


# Atlantic Reporter
    \d+\s+[Aa]\.\s?(?:\dd)?\s+\d+ - X A(.\dd)? Y

# Northwest Reporter
    \d+\s+?[Nn]\.?\s?[Ww]\.?(?:\dd)?\s+\d+ - X N.W(.\dd)? Y
    \d+\s+?[Nn]\.?\s?[Ww]\.?(?:\dd)?\s+at\s+\d+ - X N.W.(.\dd)? at Y