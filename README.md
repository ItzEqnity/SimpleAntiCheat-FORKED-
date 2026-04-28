# SimpleAntiCheat-FORKED-
Fork of SimpleAntiCheat by neonjava — added /anticheat reload, BadPackets, NoFall and Timer checks.

# SimpleAntiCheat (Fork)

> ⚠️ This is a fork of [SimpleAntiCheat](https://github.com/neonjava/simpleanticheat) originally created by **neonjava**.
> I do not claim ownership of the original code.

## What I Added
- `/anticheat reload` — reloads `config.yml` live without restarting the server
- `BadPackets` — detects illegal/malformed packets from hacked clients
- `NoFall` — detects players cancelling fall damage
- `Timer` — detects players speeding up their game tick rate
- Permission node: `autototemdetector.admin` (default: op) required to use /simpleanticheat:anticheat reload

## Usage
After editing `config.yml`, run in-game:/simpleanticheat reload
Changes apply instantly.

## Original Plugin
All credit for the core anticheat logic goes to the original author.
Check out the original repo here: [https://github.com/neonjava/simpleanticheat]

## License
This project follows the same license as the original. See [LICENSE](LICENSE)
Original work by neonjava. Fork maintained by ItzEqnity.
