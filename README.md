# Start up web browser
npm start

# Sam's Status:

- Select the suit currently equipped.

- Hazmat Suit - The suit Sam is wearing in the opening cut scenes of the game until he receives his first suit from Bridges.
- Standard Suit - First suit received from Bridges (available in Sam's private room).
- All other suits/skeletons are fabricated later in game.


# Carrying Capacity (from game UI):
- Input the KG value as shown in the Terminal UI.
- This is Sam's maximum weight carrying capcaity.


# Additional Gear Weight:
- From either the Private Locker or the Cargo Management UI
- Any gear, tools, equipment, etc. not listed in "Carried on Back" or "Attached to Suit"
- (ignore anything stored in the locker or "Not Carried")
- Sum up the weights for these items and input as a positive number
- This value will be subtracted from Sam's maximum weight capacity


# Chiralium Crystals:
- Input the value as shown in the Terminal UI.
- Sam receives a 1kg boost in maximum weight capacity for every 1000 chiralium crystals carried.
- Chiralium boost maxes out at 50kg or 50,000 crystals no matter how many more than that collected
- This will be the most difficult value to keep accurate since crystals can be used to power equipment


# Safety Buffer:
- Sam's ability to move and maneuver is severely impacted at or over maximum weight capacity
- Select a buffer for the app to factor in when determining cargo optimization to prevent fully maxing out
- The most conservative buffer is to not get within 60kg of max weight


# Credits:
- Background image was shared by スーパー初心者 Super Newb on Steam
- A huge THANK YOU! to Mike Fay @ https://mikefay.info/wiki/index.php?title=Game-Death-Stranding-Loads
    - Thanks to this wonderful rescource, we were able to back check our own findings
    - or use his research to flesh out app capabilities for things we have not reached in game yet
