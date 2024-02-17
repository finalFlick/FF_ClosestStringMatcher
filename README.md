**🛠 New Unreal Engine 5.3 Tools for Streamers: FF_ClosestStringMatcher 🛠**
https://github.com/finalFlick/FF_ClosestStringMatcher

Enhance live Twitch interactions with our latest Unreal Engine blueprints, designed for real-time viewer engagement and accurate user input handling.

No instructions? No problem @finalFlick is ready to answer your questions.

You will need to import these two files:
- content/FF/lib/BP_FF_StringUtils.uasset (the library)
- content/FF/BP_FF_ClosestStringMatcher.uasset (example uses)

**Key Benefits for Streamers:**
- Correct typos in viewer redeems automatically, matching "plae song" to "play song".
- Minimize missed or incorrect chat redeems with smart string matching.
- Quick integration into UE projects, enhancing streams without complex setup.
- Tailor content based on chat trends and improve viewer engagement with accurate responses.

**Features:**
- **Substring Filter:** Narrow down arrays by substring. Filter ["apple", "banana", "grape"] with "a" to get ["apple", "banana", "grape"].
- **Case-Insensitive Search:** Broad and flexible matching that ignores case sensitivity.
- **Numeric Extraction:** Pulls numeric characters from strings, turning "abc123def45" into "12345".
- **Number Detection:** Identifies if a string contains numbers, returning True for "abc123" and False for "abcdef".
- **N-Gram Generation:** Creates n-grams from strings for advanced text analysis, improving pattern recognition.

Ideal for Twitch streamers seeking to elevate chat interaction and redeem handling. Ensure viewer inputs are correctly interpreted and acted upon, boosting engagement and satisfaction.

Example of Closest Match:
- Search: orannge Matched:[orange]
- Search: yelloww Matched:[yellow]
- Search: gren Matched:[green]
- Search: blu Matched:[blue]
- Search: purpel Matched:[purple]
- Search: liteblue Matched:[blue]
- Search: puple2 Matched:[purple2]
- Search: pnk Matched:[pink]
- Search: blak Matched:[black]
- Search: whit Matched:[white]
- Search: ored Matched:[red]
- Search: bluee Matched:[blue]
- Search: grren3 Matched:[green3]
- Search: lightblu Matched:[lightblue]
- Search: yllow2 Matched:[yellow2]
- Search: purpl3 Matched:[purple3]
- Search: pinkk3 Matched:[pink3]
- Search: grin Matched:[green]
- Search: orang2 Matched:[orange2]
- Search: yello3 Matched:[yellow3]
- Search: blu2 Matched:[blue2]
- Search: lightblu3 Matched:[lightblue3]
- Search: purpel3 Matched:[purple3]
- Search: pink2k Matched:[pink]
