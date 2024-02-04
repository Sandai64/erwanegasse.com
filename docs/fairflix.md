# Fairflix: à propos

### Codecs & formats

> Tout média présent dans le catalogue Fairflix est transcodé à l'avance, en suivant le format suivant :

- `Container` : `MKV`
- `Framerate` : `Identique à l'original`
- `Codec` : `VP9` (Anciennement H.264)
- `Avg. Bitrate` : `2500 kbps`
- `Encoder Preset` : `Slow, Multi-Pass encoding`
- `Filters` : `Deinterlace (Decomb)`
- `Resolution Limit` : `1080p, Anamorphic Auto`
- `Audio` : `AAC @ 160, Stereo`
- `Subtitles` : `PGS, SSA`

> Note: Le codec VP9 a été choisi car il offre une bien meilleure qualité que le H.264 pour un débit similaire, cependant, certains clients comme Android TV ne le supportent pas encore. Fairflix va alors automatiquement transcoder le média au client. Il se peut que l'image apparaisse alors dégradée.
> Si c'est le cas, merci de remonter le problème à admin@fairflix.io. Indiquez le client ("l'appareil") que vous utilisez.
