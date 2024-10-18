# ECF - EVE Content Finder

A tool and website for.. well... finding content in EVE Online.

- Contact In Game: `i caress`
- Discord: https://discord.gg/qbPCe6keX4
- Donate Isk? Give to `i caress`

Supported Content Goals:
- Mirror some features for EVE Pirates Little Helper
- Support Faction Warfare via
    - Warzone Overview
        - Live Warzone Map
        - Advantage Tracking
        - Progression for flips and changed details
        - Recent activity (Change or Kills)
    - Incursion Overview
        - Where are they?
        - What other info can we get?
    - Battlefield Locator
- Support general PVP Content Via
    - Local Toon Intel
    - DScan Helper
    - Live DPS Calculator
- Support PVP Research Tooling
    - Pilot Intel
        - What ships do they favor, and what are the damage profiles / stats of them?
        - What were their past X matchups and did the win or lose?
        - Are they typically solo or in a group?
        - Who are they allied with?
    - System Intel
        - Who typically fights in this system?
        - What types of ships are typically used here?
- Support Alliances/Corporations
    - Signature Scan Recording (For example what FW plexes are in a system)
    - Tracker Intel (For example, who is in a system, dscan analysis, Intel channel analysis)
    - Wormhole Mapping (VERY VERY BASIC, last thing on my list of priorities but bonus points if we can get to it)

(Have features or suggestions you'd like to see? Open an issue or contact me on discord: https://discord.gg/qbPCe6keX4)

The system will be a combination of a local client and a web application. The web application is where general content will be stored and viewed. The local client will be used to record new content and send it to the web application. The local client will also provide some overlays and quality of life information. For instance in systems like pathfinder etc it uses the EVE ESI Api to track your location, with a local client we can use chat logs to track your location without polling and without hitting the ESI API or its limitaitons.


# Who am I?

I go by `Valindil`/`Val`/`DJ Val`/`Caress` in EVE. I've been playing EVE since 2006, and have seen most of what EVE has to offer. As many other players there are long gaps of inactivity between then and now. Back in 2017 I was heavily invested in Faction Warfare, and as such made a warzone overview map hosted at [http://jerkasauruswrecks.com/t/map/galcal/](http://jerkasauruswrecks.com/t/map/galcal/) which was used by many FW players. It is still live today, though others have taken up the mantel of extending it such as AIDER with their FW-Map addon located at: [https://aideron.org/fw/map](https://aideron.org/fw/map).

I have recently gotten back into EVE after a long hiatus and am looking to contribute to the EVE community in a positive way again. Including my love for Faction Warfare and Wormholes. 

# Inspiration

I will be taking insipiration from the following projects:

- Original Jerkasaurus FW Map: [http://jerkasauruswrecks.com/t/map/galcal/](http://jerkasauruswrecks.com/t/map/galcal/)
- AIDER FW Map: [https://aideron.org/fw/map](https://aideron.org/fw/map)
- Rift Intel Tool: [https://riftforeve.online/](https://riftforeve.online/) ([https://github.com/RiftIntelFusionTool/RIFT](https://github.com/RiftIntelFusionTool/RIFT))
- Pirates Little Helper: [http://eve-plh.com/](http://eve-plh.com/) ([https://github.com/rischwa/eve-plh](https://github.com/rischwa/eve-plh))

(Others to be added as they are located)


# TODO:

- [x] Validate the concept
- [x] Decide on the tech-stack (Python + HTMLX)
- [ ] Setup Base Web Server
- [ ] Setup ESI Authentication
- [ ] Setup Static Asset Storage & DB Schema
- [ ] Finalize v0.1 Feature List
- [ ] Figure out more todos.

# Features Requested:

- iHub vulnerability
- Metanox intel
- ESS / Skyhook intel (Is this even possible?)
- Guristas/Angel Cartel intel
- Local Analyzer
- Surrounding Systems Intel
- EVE Scout Info
- zKillboard Integration
- Integration with: https://eve-kill.com/
- DSCAN Analysis (How much max DPS is on field? Min DPS? How many reps and average rep amount?)
- Route Planning - To avoid content `;)`
- Discord Integration