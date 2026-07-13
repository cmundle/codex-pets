# Lua look mechanics

Lua looks around like a seated Maine Coon, not like a rotating cutout. Her paired white front paws, rump, and lower torso remain planted at one stable baseline. Her green eyes lead each gaze, followed by a small head yaw or pitch; the nose, muzzle, eyelids, cheek stripes, ear angle, white ruff, and upper chest follow naturally. Her fluffy tail stays grounded and may lag by only a few pixels. Preserve her calm, sweet expression and original almond-eye construction.

Motion budget: each 22.5-degree step changes eye direction, nose position, head angle, ear overlap, and ruff compression by a small even amount. No adjacent step may introduce a scale change, body slide, whole-sprite tilt, paw shift, tail-side flip, or abrupt silhouette jump.

- `000 up`: chin lifts; pupils and nose aim upward; underside of muzzle and more white throat ruff show; ears remain symmetric and paws stay planted.
- `090 screen-right`: Lua turns her head toward the image's right edge; nose and pupils clearly cross right of head center; the left cheek/ruff becomes more visible while the far right cheek is partly occluded; right ear shifts outward in profile.
- `180 down`: chin tucks toward the neatly paired paws; pupils aim downward under reshaped upper lids; forehead and ear tops become more visible while the lower muzzle compresses into the ruff.
- `270 screen-left`: Lua turns her head toward the image's left edge; nose and pupils clearly cross left of head center; the right cheek/ruff becomes more visible while the far left cheek is partly occluded; left ear shifts outward in profile.

Diagonals interpolate the neighboring cardinal pose families evenly. The eyes remain physical almond-shaped cat eyes with iris, pupil, lids, rim, and highlights moving together; do not paste floating pupils or replacement eye whites. The paws remain together throughout, matching Lua's signature resting posture.
