Campfire Exploit Restore is a Slay the Spire 2 mod that restores the pre-fix
controller/keyboard navigation exploit on the campfire smith upgrade screen.

The patch only targets `NDeckUpgradeSelectScreen` and re-enables the original
focus fallback to the card grid while an upgrade preview is open, matching the
old trigger path where d-pad/arrow navigation plus confirm could continue
selecting upgrades.
