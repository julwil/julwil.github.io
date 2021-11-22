---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<!--  -->
# Projects
## **CCD4DT**
## Visitor tracking for fairs and events
Track the position and path of trade visitors to analyze traction and gain insights into booth performance.
To improve tracking accuracy, multiple sensor types can be combined (WiFi, RFID, camera). Together with
a fellow UZH student, we developed a new system that correlates measurements of different sensors and
predicts the actual position of visitors.
- Expose REST API for ingestion of measurement data
- Kalman Filtering to remove noise
- Coordinate system standardization
- Clustering and prediction
- Persistence to InfluxDB and exposure over REST API

<img src="/assets/ccs4dt.gif" alt="CCS4DT" style="height: 300px; width:300px;"/>

<a href="https://github.com/julwil/ccs4dt" target="_blank"><img src="/assets/github.png" alt="GitHub logo" style="height: 25px; width:25px; margin-right:5px;"/>Open in GitHub</a>

`Python / Pandas / InfluxDB / Flask`

---

## **clinIQ**
## Real-Time Inventory Tracking for Hospitals
As a side project, I created the clinIQ project and founded dataloc GmbH. It’s mission is to help hospital staff find portable inventory (wheelchairs,
beds, infusion pumps) within the hospital building to save time and increase efficiency.
- Bluetooth Low Energy Beacons (tag inventory)
- Crowd-sourced, distributed inventory tracking with mobile App (on staff’s smartphone)
- Centralized processing of tracking data
- Location prediction of inventory
- Front-end to visualize inventory location

<a href="https:cliniq.ch" target="_blank"><img src="/assets/cliniq.png" alt="clinIQ logo" style="height: 25px; margin-right:5px;"/></a>

`Bluetooth Low Energy / Python / MQTT / Laravel / React`

---

## **NYC BnB Explorer**
## Explore the neighbourhoods of New York Airbnbs
Together with 3 fellow UZH students we developed a tool to explore and assess the neighbourhoods of Airbnb
listings in NYC. We collected public datasets on NYC about crime, rodent, and noise complaints. The user can
explore these datasets within the context of a particular Airbnb listing he/she is interested in.
- Display Airbnb listings on a NYC map
- Heatmap layer of crime incidents can be toggled on top of the map
- Heatmap layer of rodent sightings can be toggled on top of the map
- Heatmap layer of noise complaint incidents can be toggled on top of the map

<img src="/assets/bnb.png" alt="BnB Explorer"/>

<a href="https://github.com/UZHASE" target="_blank"><img src="/assets/github.png" alt="GitHub logo" style="height: 25px; width:25px; margin-right:5px;"/>Open in GitHub</a>

<a href="https://bnbexplorer-frontend.herokuapp.com" target="_blank"><img src="/assets/heroku.png" alt="Heroku logo" style="height: 25px; width:25px; margin-right:5px;"/>Deployed to Heroku</a>

`Python / Flask / React`

---

## **DeathNote**
## Smart contract to settle an inheritance
In the event of a death of a crypto currency holder, heirs can’t access the funds without the deceased’s private
key. Together with 3 fellow UZH students, we developed a smart contract to address this problem (we were
dead serious)
- Smart contract on the Ethereum blockchain
- Owner charges the smart contract and specifies:
- List of heirs along with their shares
- List of voters along with a policy (e.g. m/n votes required)
- Voters can vote for the owner’s death. As soon as policy is met, owner is considered dead.
- Without the owner’s objection, smart contract funds are released to heirs after 30 days

<img src="/assets/deathnote.png" alt="DeathNote" style="height: 500px; width:800px;"/>


<a href="https://github.com/UZHBCON/deathnote" target="_blank"><img src="/assets/github.png" alt="GitHub logo" style="height: 25px; width:25px; margin-right:5px;"/>Open in GitHub</a>

<a href="https://bcon-deathnote.herokuapp.com" target="_blank"><img src="/assets/heroku.png" alt="Heroku logo" style="height: 25px; width:25px; margin-right:5px;"/>Deployed to Heroku</a>

`Blockchain / Ethereum / Solidity / React`

---

## **BAZO**
## Blockchain data modification for GDPR compliance
GDPR and its application and compliance issues with blockchains is gaining attention. During my Bachelor
thesis I developed a solution that allows fine-grained update and erasure operations on transaction fields. A
cryptographic primitive called "Chameleon Hashing" enables the efficient calculation of hash collisions. These
collisions can be used to modify the content of transactions
- Implementation of Chameleon Hash function library in Go
- Integration of new hashing mechanism in existing BAZO blockchain and its protocol
- Implementation of "update transactions" to modify on-chain data
- Implementation of a web-based block explorer to visualize the results


<img src="/assets/baz_miner_sequence_diagram.jpg" title="Sequence of an update" alt="Sequence diagram" style="height: 400px; width:800px;"/>

Sequence of an UpdateTx

<img src="/assets/before_rectification.PNG" title="AccountTX (Before update)" alt="AccountTX (Before update)" style="height: 250px;"/>

AccountTX (Before update)

<img src="/assets/updatetx.png" title="UpdateTX" alt="UpdateTX" style="height: 250px;"/>

UpdateTX

<img src="/assets/after_rectification.PNG" title="Account TX (After update)" alt="Account TX (After update)" style="height: 250px;"/>

Account TX (After update)

<a href="https://github.com/julwil/bazo-miner" target="_blank"><img src="/assets/github.png" alt="GitHub logo" style="height: 25px; width:25px; margin-right:5px;"/>Open in GitHub</a>

`Blockchain / Go / React`

---

## Santorini
We created a digital version of the game [Santorini](https://roxley.com/products/santorini). The challenge on the front-end was to emulate the board game and provide the possibility to create buildings and move figures. On the back-end side, the challenge was to implement the game logic (e.g. rules and superpowers of the individual game characters).
- Board game visualiation
- Player matchup (Lobby)
- Multiplayer version
- Implement rules and superpowers

<img src="/assets/santorini2.png" title="Challenge User" alt="Board" style=""/>

Challenge User

<img src="/assets/santorini.png" title="Board" alt="Board" style=""/>

Santorini Game

<a href="https://github.com/julwil/santorini-server" target="_blank"><img src="/assets/github.png" alt="GitHub logo" style="height: 25px; width:25px; margin-right:5px;"/>Open in GitHub</a>

<a href="https://sopra-willems-julius-client.herokuapp.com" target="_blank"><img src="/assets/heroku.png" alt="Heroku logo" style="height: 25px; width:25px; margin-right:5px;"/>Deployed to Heroku</a>

`Java / SpringBoot / React`