# Configurations for Manjaro to work in shcool

# SAMSUNG ML-2571 printer

remove line number 229 from the ppd file (`/etc/cups/ppd/SAMSUNG-ML-2570.ppd`)
```
227 | *% These provide the physical dimensions of the media, by option keyword.
228 | *DefaultPaperDimension: A4
229 | *PaperDimension A4/A4: "842 1190"                <------- this line is wrong
230 | *PaperDimension Letter/Letter: "612 792"
231 | *PaperDimension Legal/Legal: "612 1008"
232 | *PaperDimension A4/A4: "595 842"
```
