Example use:

```cpp
// Get local player tits size (if it's a female) and penis size other wise.

float value = local_player->get_morph_value("Global Body", "breast");

// Value returned between 0.0 and 1.0 (0% to 100%)
```

```cpp
// Set local player tits size (if it's a female) and penis size other wise.

local_player->apply_morph_value("Global Body", "breast", 1.0);

// In this case the value is set to 1.0 (100%)
// using a value higher than 1.0 not especially increase the size even more,
// in most cases it simply cause weird stuff to happen (Like broken bones or weird physic).
```

```json
{
    "Brow": {
        "brow depth": "BROW DEPTH",
        "brow spacing": "BROW SPACING",
        "brow width": "BROW WIDTH",
        "inner brow elevation": "INNER BROW HEIGHT",
        "middle brow elevation": "MIDDLE BROW HEIGHT",
        "outer brow elevation": "OUTER BROW HEIGHT"
    },
    "Cheekbones": {
        "cheekbones depth": "CHEEKBONE DEPTH",
        "cheekbones elevation": "CHEEKBONE HEIGHT",
        "cheekbones size": "CHEEKBONE SIZE",
        "cheekbones spacing": "CHEEKBONE SPACING",
        "cheeks depth": "CHEEK DEPTH",
        "cheeks elevation": "CHEEK HEIGHT",
        "cheeks spacing": "CHEEK SPACING",
        "jowls depth": "JOWL DEPTH",
        "jowls elevation": "JOWL HEIGHT",
        "jowls spacing": "JOWL SPACING",
        "temples depth": "TEMPLE DEPTH",
        "temples elevation": "TEMPLE HEIGHT",
        "temples spacing": "TEMPLE SPACING"
    },
    "Chin": {
        "chin depth": "CHIN DEPTH",
        "chin elevation": "CHIN ELEVATION",
        "chin height": "CHIN HEIGHT",
        "chin width": "CHIN WIDTH",
        "double chin depth": "DOUBLE CHIN DEPTH",
        "double chin elevation": "DOUBLE CHIN HEIGHT",
        "double chin width": "DOUBLE CHIN WIDTH"
    },
    "Crown": {
        "neck back depth": "NECK BACK DEPTH",
        "neck back width": "NECK BACK WIDTH",
        "skull back depth": "SKULL BACK DEPTH",
        "skull back width": "SKULL BACK WIDTH",
        "skull top elevation": "SKULL TOP HEIGHT",
        "skull top width": "SKULL TOP WIDTH"
    },
    "Ears": {
        "ears depth": "EAR DEPTH",
        "ears elevation": "EAR ELEVATION",
        "ears height": "EAR HEIGHT",
        "ears length": "EAR LENGTH",
        "ears pitch": "EAR ANGLE",
        "ears roll": "EAR ROLL",
        "ears spacing": "EAR SPACING",
        "ears width": "EAR WIDTH",
        "ears yaw": "EAR OPENNESS",
        "lobes elevation": "LOBE HEIGHT",
        "lobes size": "LOBE SIZE",
        "tips elevation": "TIP HEIGHT",
        "tips size": "TIP SIZE",
        "tips spacing": "TIP SPACING"
    },
    "Eyes": {
        "eye folds elevation": "EYE FOLDS HEIGHT",
        "eye style": "EYE STYLE",
        "eyeballs depth": "EYEBALL DEPTH",
        "eyeballs elevation": "EYEBALL HEIGHT",
        "eyeballs size": "EYEBALL SIZE",
        "eyeballs spacing": "EYEBALL SPACING",
        "iris size": "IRIS SIZE",
        "lower eyelids pitch": "LOWER EYELID HEIGHT",
        "upper eyelids pitch": "UPPER EYELID HEIGHT"
    },
    "Forehead": {
        "forehead depth": "FOREHEAD DEPTH",
        "forehead elevation": "FOREHEAD HEIGHT",
        "forehead width": "FOREHEAD WIDTH"
    },
    "Global Body": {
        "body fat": "FATNESS",
        "body muscle": "MUSCULARITY",
        "body skinny": "BODY",
        "breast": "BODY SHAPE",
        "old": "AGE PRESETS"
    },
    "Global Face": {
        "asian": "ASIAN",
        "black": "!!Player Morph Black Text",
        "face age": "FACE AGE",
        "white": "!!Player Morph White Text"
    },
    "Global Gender": {
        "body gender": "!!Player Morph Body Gender Text",
        "face gender": "!!Player Morph Face Gender Text"
    },
    "Jaw": {
        "jaw depth": "JAW DEPTH",
        "jaw elevation": "JAW HEIGHT",
        "jaw spacing": "JAW SPACING"
    },
    "Mouth": {
        "lower lip middle elevation": "LOWER LIP MIDDLE HEIGHT",
        "lower lip middle size": "LOWER LIP MIDDLE SIZE",
        "lower lip sides elevation": "LOWER LIP SIDE HEIGHT",
        "lower lip sides size": "LOWER LIP SIDE SIZE",
        "mouth bite": "MOUTH BITE",
        "mouth depth": "MOUTH DEPTH",
        "mouth elevation": "MOUTH ELEVATION",
        "mouth sides depth": "MOUTH SIDE DEPTH",
        "mouth sides elevation": "MOUTH SIDE HEIGHT",
        "mouth sides size": "MOUTH SIDE SIZE",
        "mouth size": "MOUTH STYLE",
        "mouth width": "MOUTH WIDTH",
        "upper lip middle elevation": "UPPER LIP MIDDLE HEIGHT",
        "upper lip middle size": "UPPER LIP MIDDLE SIZE",
        "upper lip sides elevation": "UPPER LIP SIDE HEIGHT",
        "upper lip sides size": "UPPER LIP SIDE SIZE"
    },
    "Nose": {
        "ball depth": "TIP DEPTH",
        "ball elevation": "TIP ELEVATION",
        "ball height": "TIP HEIGHT",
        "ball width": "TIP WIDTH",
        "bridge depth": "BRIDGE DEPTH",
        "bridge elevation": "BRIDGE HEIGHT",
        "bridge width": "BRIDGE WIDTH",
        "nose depth": "NOSE DEPTH",
        "nose elevation": "NOSE ELEVATION",
        "nose style": "NOSE STYLE",
        "nostrils depth": "NOSTRIL DEPTH",
        "nostrils elevation": "NOSTRIL ELEVATION",
        "nostrils height": "NOSTRIL HEIGHT",
        "nostrils spacing": "NOSTRIL SPACING",
        "nostrils width": "NOSTRIL WIDTH",
        "septum elevation": "SEPTUM HEIGHT",
        "septum width": "SEPTUM WIDTH",
        "slope depth": "SLOPE DEPTH",
        "slope elevation": "SLOPE HEIGHT",
        "slope width": "SLOPE WIDTH"
    }
}
```
