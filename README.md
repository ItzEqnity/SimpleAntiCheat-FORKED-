# SimpleAntiCheat-FORKED-
Fork of SimpleAntiCheat by neonjava — added /anticheat reload, BadPackets, NoFall, Timer checks. Removed reach & hitbox flags.

# SimpleAntiCheat (Fork)

> ⚠️ This is a fork of [SimpleAntiCheat](https://github.com/neonjava/simpleanticheat) originally created by **neonjava**.
> I do not claim ownership of the original code.

## What I Added / Changed
- `/anticheat reload` — reloads `config.yml` live without restarting the server
- `BadPackets` — detects illegal/malformed packets from hacked clients
- `NoFall` — detects players cancelling fall damage (configurable per world)
- `Timer` — detects players speeding up their game tick rate
- Removed reach & hitbox flags completely

## All Features
| Check | Description |
|---|---|
| AutoTotem | Detects automated totem refilling |
| AnchorSpam | Detects automated respawn anchor spam |
| CrystalSpam | Detects automated end crystal spam |
| BadPackets | Detects illegal/malformed packets |
| NoFall | Detects fall damage cancellation |
| Timer | Detects game tick speedup |

## Commands
| Command | Description | Permission |
|---|---|---|
| `/anticheat reload` | Reloads config.yml instantly | `autototemdetector.admin` |

## Permissions
| Permission | Description |
|---|---|
| `simpleanticheat.alerts` | Receive hack alerts |
| `autototemdetector.admin` | Use /anticheat reload |
| `simpleanticheat.badpackets.bypass` | Bypass BadPackets |
| `simpleanticheat.nofall.bypass` | Bypass NoFall |
| `simpleanticheat.timer.bypass` | Bypass Timer |

## NoFall World Config
In `config.yml` add the worlds you want NoFall active in:
```yaml
no-fall:
  worlds:
    - world
    - world_nether
```
If the list is empty, NoFall won't run in any world.

## Usage
After editing `config.yml`, run in-game:
```
/anticheat reload
```
Changes apply instantly without restarting the server.

## Original Plugin
All credit for the core anticheat logic goes to the original author.
Check out the original repo here: [https://github.com/neonjava/simpleanticheat]

## License
This project follows the same license as the original. See [LICENSE](LICENSE)
Original work by neonjava. Fork maintained by ItzEqnity.
