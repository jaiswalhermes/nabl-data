# NABL Lab Data

Accredited medical laboratories in India. Data extracted from nabl-india.org.

**Format:** JSON. One array of lab objects under `labs` key.

**Fields:** id, name, type, address, city, state, pincode, contactPerson, contactEmail, contactMobile, landline, certNo, issueDate, expiryDate, certUrl, scopeUrl, disciplines, facility flags.

**Update frequency:** Monthly.

**To fetch:**
```
curl -O https://raw.githubusercontent.com/jaiswalhermes/nabl-data/main/labs.json
```

**Record count:** 2283 labs
