# [The Finals](https://store.steampowered.com/app/2073850/THE_FINALS)

Workaround due to [Embark Studios](https://www.embark-studios.com) discontinued support of [Steam Input](https://partner.steamgames.com/doc/features/steam_controller) integrated Gamepad and High Precision Controllers.  This template provides keyboard mapping that _loosely mimics_ the [Steam Controller](https://store.steampowered.com/app/353370/Steam_Controller) behavior.

**UPDATE:** It seems that as of 8/4 Embark has [finally recognized this as an issue](https://discord.com/channels/1008696016318513243/1398020088116023366/1401941186113179679) so I assume it will be fixed in a future (patch) release.

## Nuxy's Gamepad With Camera Controls (WASD mapping)

This configuration is available and can be installed from: **Load new layout > Community Profiles**

![Preview](https://raw.githubusercontent.com/nuxy/Steam-Input-Gamepad-Settings/refs/heads/master/Steam%20Controller%20Config/The%20Finals/preview.png)

## Notable differences from HPC layouts

For the mostpart, the game is playable but there are noticeable differences between the game HPC integration and using a WASD layout.  I have listed the ones I noticed while playing below.  Note, this list will be updated as new issues arise.  In most cases they can be mitigated using [Steam Input](https://partner.steamgames.com/doc/features/steam_controller) while others need to be addressed by the game developers themselves.

### Multipurpose buttons usage

The game currently handles controller button bindings that serve multiple purposes.  Buttons may perform different operations based on the context (e.g. in-game action vs menu operations).

In this layout these operations are implemented as separate controller bindings.

### Button processing delay

There can be a slight delay when performing sequential operations.

#### Example

- Performing a **Use/Sprint/Jump** while changing directions may contain a slight lag.
- Performing a **Slide** action after a **Jump** may prematurely stop at a **Crouch**.
