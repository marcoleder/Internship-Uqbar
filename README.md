# Extension of the uqbar wallet and its features
In this repository I will log both the completed tasks for the current day and the tasks for the upcoming day. My commits reside in the uqbar repository: https://github.com/uqbar-dao/ziggurat

## Week 1

### Day 1
After *several hours* of troubleshooting my L2 ship `~ticsun-rigpen` I finally... decided to give up. I bought a new planet on L1 `~roslug-fampet` and set it up on a local raspberry pi 4 server. I am still waiting for confirmation if everything works, especially the install of EScape and the ability to join groups and chat.
#### Completed tasks (CT):
- Setup VScode for hoon programming
- Cloned repository ziggurat
- Troubleshooted `~ticsun-rigpen`
- Setup umbrel with urbit on localhost with ID `~roslug-fampet`
- Repeated hoon topic: type polymorphism

#### To do tomorrow (TDT):
- Verify umbrel + urbit setup
- Chat with `~taller-ravnut` & `~wolref-podlex` about salary
- Weekly dev meeting
- Repeat hoon topic: wet & dry
- Get to know working environment and developer practices of the team

### Day 2
WELP, the ship was still not working as expected. I have encountered a "upgrade the runtime" error, but eventually was able to fix it (finally). My ship now sails the digital ocean as a droplet, paired with S3 storage, also from digital ocean. I gave up on pairing urbit with umbrel, tbh, urbit runs best as is (that is, standalone on a linux system). With my ship running, I was able complete my tasks and continue onboarding.
#### CT:
- Switched from umbrel to digital ocean
- Conversation *started* with `~taller-ravnut` & `~wolref-podlex` about salary
- Weekly dev meeting
- Repeated hoon topic: wet & dry
- Got to know the team's developer practices (by examining github)

#### TDT:
- Troubleshoot hoon-language-server
- Meet with `~hodzod-walrus` to discuss github workflow
- Repeat hoon topic: Behn, vanes, gall
- Setup ziggurat repo according to its readme.md
- Attend & hopefully pass my last university exam ;-)

### Day 3
Examination day went well, now I can level-up my commitment from 70% to 100%. Had a meeting today with `~hodzod-walrus` and he onboarded me with the developer workflow, how to sync folders live to the local fake-ship and the general practices the uqbar dev team applies throughout the day. Furthermore I revisited some important chapters of the hoon school again, getting ready to contribute soon.
#### CT:
- *Started* hoon-language-server troubleshooting, no success yet
- Met with `~hodzod-walrus` to discuss github workflow
- Repeated hoon topics: Behn, vanes, gall
- Setup ziggurat repo with working environment
- Officially finished my university semester

#### TDT:
- Finish hoon-language-server issues by contacting `~littel-wolfur`
- Setup code environment as `~hodzod-walrus` suggested
- Figure out how to run contracts in ziggurat/mill.hoon
- Examine [wallet.hoon](https://github.com/uqbar-dao/ziggurat/blob/master/app/wallet.hoon) and get an understanding of its workings
- Examine [smart.hoon](https://github.com/uqbar-dao/ziggurat/blob/master/lib/zig/sys/smart.hoon) and get an understanding of its workings

### Day 4
I ran into some issues when commiting to the %zig desk, see output below. I still could not find the root of this cause, but have contacted the corresponding people to help me. Furthermore, had a chat with the other intern `~sipfyn-pidmex` and he gave me some important onboarding tips as well. The coding environment which I have set up according to `~hodzod-walrus`'s suggestion took longer than excepted, but I can now successfully run "watch.sh rsync -zr -delete * ~/fakeships/zod/zig" which will save me a lot of time in the future.
#### CT:
- *Continued* troubleshooting hoon-language-server, but `~littel-wolfur` was not in the office due to his car crash, hence still not fixed
- Setup code environment as `~hodzod-walrus` suggested
- *Started* tinkering on how to run smart contracts but due to the issue mentioned in the description, no success yet
- Examined both [wallet.hoon](https://github.com/uqbar-dao/ziggurat/blob/master/app/wallet.hoon) & [smart.hoon](https://github.com/uqbar-dao/ziggurat/blob/master/lib/zig/sys/smart.hoon)
- Started to look at "uhoon"

#### TDT:
- Finish hoon-language-server issues *for real*
- Fix error which still hinders smart contract execution
- Look at [fungible.hoon](https://github.com/uqbar-dao/ziggurat/blob/master/lib/zig/contracts/fungible.hoon)
- Conversation with `~taller-ravnut` & `~wolref-podlex` about salary must finish in order to sign contract
- Repeat hoon topic: Hoon 201

Error when running |commit %zig

`crud: %into event failed`<br />
`[%poke %into]`<br />
`bar-stack=~[~[//sync/0v1p.5mu3o]]`<br />
`call: failed`<br />
`/sys/vane/clay/hoon:<[4.229 3].[4.495 5]>`<br />
`/sys/vane/clay/hoon:<[4.231 3].[4.495 5]>`<br />
`/sys/vane/clay/hoon:<[4.235 3].[4.495 5]>`<br />
`/sys/vane/clay/hoon:<[4.238 3].[4.495 5]>`<br />
`/sys/vane/clay/hoon:<[4.316 5].[4.330 15]>`<br />
`/sys/vane/clay/hoon:<[4.317 5].[4.330 15]>`<br />
`/sys/vane/clay/hoon:<[4.318 5].[4.330 15]>`<br />
`/sys/vane/clay/hoon:<[4.320 5].[4.330 15]>`<br />
`/sys/vane/clay/hoon:<[4.324 5].[4.330 15]>`<br />
`/sys/vane/clay/hoon:<[4.325 5].[4.330 15]>`<br />
`/sys/vane/clay/hoon:<[4.327 5].[4.330 15]>`<br />
`/sys/vane/clay/hoon:<[4.328 7].[4.329 44]>`<br />
`/sys/vane/clay/hoon:<[4.329 7].[4.329 44]>`<br />
`/sys/vane/clay/hoon:<[4.329 12].[4.329 44]>`<br />
`/sys/vane/clay/hoon:<[1.696 5].[1.713 47]>`<br />
`/sys/vane/clay/hoon:<[1.699 5].[1.713 47]>`<br />
`/sys/vane/clay/hoon:<[1.709 5].[1.713 47]>`<br />
`/sys/vane/clay/hoon:<[1.713 5].[1.713 47]>`<br />
`/sys/vane/clay/hoon:<[1.670 5].[1.690 26]>`<br />
`/sys/vane/clay/hoon:<[1.671 5].[1.690 26]>`<br />
`/sys/vane/clay/hoon:<[1.677 5].[1.690 26]>`<br />
`/sys/vane/clay/hoon:<[1.678 5].[1.690 26]>`<br />
`/sys/vane/clay/hoon:<[1.689 5].[1.690 26]>`<br />
`/sys/vane/clay/hoon:<[1.690 5].[1.690 26]>`<br />
`/sys/vane/clay/hoon:<[1.725 5].[1.828 41]>`<br />
`/sys/vane/clay/hoon:<[1.726 5].[1.828 41]>`<br />
`/sys/vane/clay/hoon:<[1.729 5].[1.828 41]>`<br />
`/sys/vane/clay/hoon:<[1.734 5].[1.828 41]>`<br />
`/sys/vane/clay/hoon:<[1.742 5].[1.828 41]>`<br />
`/sys/vane/clay/hoon:<[1.742 19].[1.742 36]>`<br />
`/sys/vane/clay/hoon:<[1.844 7].[1.879 9]>`<br />
`/sys/vane/clay/hoon:<[1.845 7].[1.879 9]>`<br />
`/sys/vane/clay/hoon:<[1.845 11].[1.861 13]>`<br />
`/sys/vane/clay/hoon:<[1.853 13].[1.860 15]>`<br />
`/sys/vane/clay/hoon:<[1.857 13].[1.860 15]>`<br />
`/sys/vane/clay/hoon:<[1.858 21].[1.858 41]>`<br />
`/sys/vane/clay/hoon:<[1.872 9].[1.878 11]>`<br />
`/sys/vane/clay/hoon:<[1.873 9].[1.878 11]>`<br />
`/sys/vane/clay/hoon:<[1.876 11].[1.877 48]>`<br />
`/sys/vane/clay/hoon:<[1.877 11].[1.877 48]>`<br />
`/sys/vane/clay/hoon:<[1.877 19].[1.877 47]>`<br />
`/sys/vane/clay/hoon:<[1.877 31].[1.877 46]>`<br />
`{1 12}`<br />
`syntax error`

### Day 5
What a first week - I learnt very much around the topic "setup urbit development environment" and also got an answer to the question: "Where does urbit run the best?" *Linux*, trust me... With that said, my 5th day consisted mainly of me switching my setup over to linux, doing the whole repo & urbit setup there, finally bringing me to a point where the language server does not throw any errors anymore and I can use my VScode to modify the files in linux via a websocket connection.
#### CT:
- Finished hoon-language-server setup, many thanks to `~littel-wolfur` for the help!
- Progressed with smart contracts execution
- Looked at [fungible.hoon](https://github.com/uqbar-dao/ziggurat/blob/master/lib/zig/contracts/fungible.hoon)
- `~taller-ravnut`, `~wolref-podlex` and I concluded that they give the star to urbit, in exchange I receive monthly payments from uqbar
- Repeated hoon topic: Hoon 201, part a)

#### TDT:
- Fix smart contracts error
- Go over [wallet.hoon](https://github.com/uqbar-dao/ziggurat/blob/master/app/wallet.hoon), maybe clean up the repetitive %submit-custom, %submit-signed and %submit arms
- Change from fakeship to moon for development in order to be able to install argo
- Repeat hoon topic: Hoon 201

## Week 2

### Day 6
Had a talk with `~hocwyn-tipwex` about general onboarding, questions and work-environment. Troubleshooted %argo by `~littel-wolfur`, connection established and working but encountering new errors (see below). While going over [wallet.hoon](https://github.com/uqbar-dao/ziggurat/blob/master/app/wallet.hoon) I quickly also took a look at [wallet-ui](https://github.com/uqbar-dao/wallet-ui) and stumbled over a block of if-statements, hence applied small refactoring.
#### CT:
- Went over [wallet-ui](https://github.com/uqbar-dao/wallet-ui), saw room for improvement, made [PR](https://github.com/uqbar-dao/wallet-ui/pull/4)
- Fixed error when commiting to desk %zig
- Repeated hoon topic: Hoon 201, part b)
- Booted moon `~hosdex-hodsud-roslug-fampet` for development, successfully installed argo

#### TDT:
- Fix %argo error
- uHoon deeper dive
- After [whitelist PR](https://github.com/uqbar-dao/ziggurat/pull/84) merge, run blockchain & use wallet

Error when hovering over runes

`poke failed from %language-server on wire /lsp`<br />
`/app/language-server/hoon:<[376 5].[376 29]>`<br />
`/app/language-server/hoon:<[375 3].[409 44]>`<br />
`/app/language-server/hoon:<[374 3].[409 44]>`<br />
`/app/language-server/hoon:<[373 3].[409 44]>`<br />
`/app/language-server/hoon:<[372 3].[409 44]>`<br />
`/app/language-server/hoon:<[371 3].[409 44]>`<br />
`/app/language-server/hoon:<[144 67].[144 85]>`<br />
`/app/language-server/hoon:<[144 39].[144 85>`<br />
`/app/language-server/hoon:<[142 5].[146 7]>`<br />
`/app/language-server/hoon:<[141 3].[147 16]>`<br />
`/app/language-server/hoon:<[140 3].[147 16>`<br />
`/app/language-server/hoon:<[88 9].[88 54]>`<br />
`/app/language-server/hoon:<[84 7].[89 9]>`<br />
`/app/language-server/hoon:<[83 5].[90 17]>`<br />
`/app/language-server/hoon:<[82 5].[90 17]>`<br />
`/sys/vane/gall/hoon:<[1.372 9].[1.372 37]>`<br />

### Day 7
Gave up on troubleshooting the hoon-language-server, `~littel-wolfur` thanks again for all the help to get this far, but despite the sunk costs I will have to let this one go due to time constraints. Then another letdown, realized that uHoon is just adding new abstractions but syntax remains the same, so nothing really new to learn there as the abstractions make sense (mostly). Finally though, I was able to run and join a testnet, nice!
#### CT:
- Ran testnet without issues, still having trouble with wallet though
- Conceptually understood uHoon abstractions
- Dev meeting with outlook on future tasks (more broad)

#### TDT:
- Get wallet up & running with the testnet
- Let DAO agent watch the indexer & change DAO states
- Find parts in [wallet.hoon](https://github.com/uqbar-dao/ziggurat/blob/master/app/wallet.hoon) which need to be cleaned up
- Come up with strategies on how to improve those parts of [wallet.hoon](https://github.com/uqbar-dao/ziggurat/blob/master/app/wallet.hoon)

### Day 8
Today I tried to setup the wallet and the DAO agent, however, I ran into some issues concering my setup... Even though I switched to linux, I still need to get used to some of the quirks of hoon, urbit and linux as a whole new operating system. I was able to examine the wallet app though, get a more thorough understanding and came up with an idea on how to eliminate the repeated arms in the file.
#### CT:
- Wallet setup troubleshooting, not yet working
- DAO agent troubleshooting, not yet working
- Examined [wallet.hoon](https://github.com/uqbar-dao/ziggurat/blob/master/app/wallet.hoon)
- Thought of way how to clean up %submit-custom, %submit-signed and %submit

#### TDT:
- Take a look at new [hoon school](https://developers.urbit.org/guides/core/hoon-school) guide
- Fix wallet & DAO agent
- Create design draft for [wallet.hoon](https://github.com/uqbar-dao/ziggurat/blob/master/app/wallet.hoon) for refactoring %submit-custom, %submit-signed and %submit

### Day 9
Today I examined the new hoon school guide, looked at topics to see if I have missed anything and started to work on app school. Furthermore, I tried to apply further issue solving techniques to DAO agent and wallet, still no luck tho. Mainly I spent my time revising the idea on how to eliminate the repetitive arms of [wallet.hoon](https://github.com/uqbar-dao/ziggurat/blob/master/app/wallet.hoon), focusing on %submit-custom, %submit-signed and %submit arms.
#### CT:
- Quickly worked through hoon school again
- Started on [app school I](https://developers.urbit.org/guides/core/app-school)
- Created design for [wallet.hoon](https://github.com/uqbar-dao/ziggurat/blob/master/app/wallet.hoon)

#### TDT:
- Finish [app school I](https://developers.urbit.org/guides/core/app-school)
- Start & finish [app school II](https://developers.urbit.org/guides/core/app-school-full-stack)
- Implement design for [wallet.hoon](https://github.com/uqbar-dao/ziggurat/blob/master/app/wallet.hoon)

### Day 10
Today I finished both app school I and II, leaving all "catching up & learning" aside for the future. I now have a complete overview over gall, hoon, etc etc. Furthermore I started to implement my changes for the wallet app, but due to syntax errors I have not yet made a PR. I will hope to be able to do this over the course of the next few days, by resolving all errors and finishing the implementation of my refactoring idea.
#### CT:
- Finished app school I
- Finished app school II
- Started on implementation of [wallet.hoon](https://github.com/uqbar-dao/ziggurat/blob/master/app/wallet.hoon) refactoring

#### TDT:
- Finish implemetation of [wallet.hoon](https://github.com/uqbar-dao/ziggurat/blob/master/app/wallet.hoon) refactoring, %submit-custom, %submit-signed and %submit sections

## Week 3

### Day 11
My day consisted mostly of continuing my work on refactoring [wallet.hoon](https://github.com/uqbar-dao/ziggurat/blob/master/app/wallet.hoon) and focusing on the duplicated code in %submit-custom, %submit-signed and %submit sections. A fraction of my time was also dedicated towards fixing my display issues such that I can work on my big monitor again. Overall I think I am on track and can have the refactoring finished by wednesday. Furthermore, I had a quick talk with my university about remote work, which they thankfully approved.
#### CT:
- Continued with implementation of [wallet.hoon](https://github.com/uqbar-dao/ziggurat/blob/master/app/wallet.hoon) refactoring
- Troubleshooted linux display xrandr
- Email conversation with university concering remote work setting

#### TDT:
- Finish implemetation in [wallet.hoon](https://github.com/uqbar-dao/ziggurat/blob/master/app/wallet.hoon)