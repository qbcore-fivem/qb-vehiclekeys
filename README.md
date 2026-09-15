# qb-vehiclekeys
Vehicle Keys System For QB-Core

# Vehicle Key NUI Preview
[[Preview Here]](https://www.youtube.com/watch?v=7E9TXR3lXPI)

# Exports

Server side. These are the supported integration points for other resources; do not
trigger the internal net events directly.

```lua
-- Grant a player keys to a plate. Omit the plate to use the vehicle the player is in.
exports['qb-vehiclekeys']:GiveKeys(source, plate)

-- Revoke a player's keys to a plate.
exports['qb-vehiclekeys']:RemoveKeys(source, plate)

-- Returns whether a player holds keys to a plate.
exports['qb-vehiclekeys']:HasKeys(source, plate)
```

# License

    QBCore Framework
    Copyright (C) 2021 Joshua Eger

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>
