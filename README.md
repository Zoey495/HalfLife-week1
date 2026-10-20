# HalfLife
Code for HalfLife week 1, project Starbie.
JOURNAL.md & BOM.md are directly transferred from Half Life themselves.

This project is about making a digital pet.

There are two buttons, a screen, a chip, temperature/humidity sensor, and a gyroscope.

Using the two buttons, ideally, you would select a option out of four and cause the digital pet to take that action.
The digital pet has 3 energy bars representing different things like sleep.

This right here is the Starbie's (digital pet) schematic diagram

<img width="498" height="494" alt="Screenshot at 2026-10-06 19-55-36" src="https://github.com/user-attachments/assets/6c1682b7-3db4-49e9-8fd5-ff0c01041995" />

A schematic diagram describes how several components will be connected together.


Using KiCad, I created the PCB from the schematic diagram, the board where all these components would connect to and work together. I would then have to solder (connect the components to the board using a special type of metal) them once they physically are here. 

<img width="694" height="547" alt="image" src="https://github.com/user-attachments/assets/c7780886-3c66-49c1-bf04-fdddb8efab4f" />

This image is the 3D view that KiCad has for PCBs.

As of right now, it has only been designed and is not built yet.


| Part | What it's for | Qty | Unit | Total | Vendor |
| --- | --- | --- | --- | --- | --- |
| [XIAO ESP32 C3](https://www.seeedstudio.com/Seeed-XIAO-ESP32C3-p-5431.html) | Starbie's brain/CPU | 1 | $4.90 | $4.90 | [Seeed Studio](https://www.seeedstudio.com/Seeed-XIAO-ESP32C3-p-5431.html) |
| [0.96 OLED](https://www.amazon.com/dp/B0GBVWBWCR) | LED screen for starbie | 1 | $5.99 | $5.99 | [amazon](https://www.amazon.com/dp/B0GBVWBWCR) |
| [DHT11](https://www.amazon.com/Digital-Temperature-Humidity-Sensor-Module/dp/B0G2BGJSMV/ref=sr_1_10?crid=C9YUFB26HVOO&dib=eyJ2IjoiMSJ9.LkMWw0X9tvBpaqYzu4yUbzf5eF1dP5Nqf1uOXYtczXn_Fc6k08oVPsUku_juWFpWRohZbhw4OPTvqTpesF7YiC7tc3htagrOEur2PwP2eEGa8f-7q9YXiDjJGap1-GASNbpG94zdcvHXSU7gIqPiFC1VfNlqD1-sAwBBGzB8s6UmRbJhahHcxftfrMp3Efv48oYVj2XOvne3_JEzGJEw_eI4yMrJA7FUg2LMe7kyzvORVLTMxUVbFLiTipEpcTb6zBNIUDkP6xIvpI6gWw1ctFhoJkqQzkEyrUy9XNFeNLI.DcBrZqgsKwaGZAYTnqH7DrFwpG9lrMlvCy3asReYxEM&dib_tag=se&keywords=DHT11&qid=1791773804&refinements=p_76%3A1249158011&rnid=1249156011&rps=1&s=industrial&sprefix=dht11%2Cindustrial%2C144&sr=1-10) | Temperature and Humidity sensor for Starbie | 1 | $6.64 | $6.64 | [Amazon](https://www.amazon.com/Digital-Temperature-Humidity-Sensor-Module/dp/B0G2BGJSMV/ref=sr_1_10?crid=C9YUFB26HVOO&dib=eyJ2IjoiMSJ9.LkMWw0X9tvBpaqYzu4yUbzf5eF1dP5Nqf1uOXYtczXn_Fc6k08oVPsUku_juWFpWRohZbhw4OPTvqTpesF7YiC7tc3htagrOEur2PwP2eEGa8f-7q9YXiDjJGap1-GASNbpG94zdcvHXSU7gIqPiFC1VfNlqD1-sAwBBGzB8s6UmRbJhahHcxftfrMp3Efv48oYVj2XOvne3_JEzGJEw_eI4yMrJA7FUg2LMe7kyzvORVLTMxUVbFLiTipEpcTb6zBNIUDkP6xIvpI6gWw1ctFhoJkqQzkEyrUy9XNFeNLI.DcBrZqgsKwaGZAYTnqH7DrFwpG9lrMlvCy3asReYxEM&dib_tag=se&keywords=DHT11&qid=1791773804&refinements=p_76%3A1249158011&rnid=1249156011&rps=1&s=industrial&sprefix=dht11%2Cindustrial%2C144&sr=1-10) |
| [MX Switches](https://www.amazon.com/FRCTLNKG-Clickers-Prints-Keyboard-Clicker/dp/B0GJDV3TQL/ref=sr_1_2?crid=2HEGS3PC9TMCJ&dib=eyJ2IjoiMSJ9.aEtT3Y9qkJJwWqxjuibzxc8H4L01MqVaQJV0G8crpyzsC10093AbHzkrpBRO-Fs5D82_qgWhVfpZl6uvSb4shToOO1obXlV-widDpdBdByHIbIfveK2ocfPaw4qbP4jkUnP16oH0do3gnx-V9tAWtvbI5m8rREkU1cvICjegWC7fifFE6kn-zYBtsuKV-DsetVqPVjWp_u7EXbx6HgSwZ-hNgTFqKsKUNN8pBp1PVo-6x8sbQpxVARHOfm_f4wiP0OiMr2pNmgn8eymW0RIXLIK_FyePUdUTZXHfRn1_ibE.OiRRLcZtoW5JnUQTyJ2dQ8_O6nPuidCR1X7wzPNK1kg&dib_tag=se&keywords=Keyboard+Switches&qid=1791773926&refinements=p_76%3A1249158011&rnid=1249156011&rps=1&s=industrial&sprefix=keyboard+switches%2Cindustrial%2C120&sr=1-2) |To indicate to the chip what option I wish to select | 2 | $3.29 | $3.29 | [Amazon](https://www.amazon.com/FRCTLNKG-Clickers-Prints-Keyboard-Clicker/dp/B0GJDV3TQL/ref=sr_1_2?crid=2HEGS3PC9TMCJ&dib=eyJ2IjoiMSJ9.aEtT3Y9qkJJwWqxjuibzxc8H4L01MqVaQJV0G8crpyzsC10093AbHzkrpBRO-Fs5D82_qgWhVfpZl6uvSb4shToOO1obXlV-widDpdBdByHIbIfveK2ocfPaw4qbP4jkUnP16oH0do3gnx-V9tAWtvbI5m8rREkU1cvICjegWC7fifFE6kn-zYBtsuKV-DsetVqPVjWp_u7EXbx6HgSwZ-hNgTFqKsKUNN8pBp1PVo-6x8sbQpxVARHOfm_f4wiP0OiMr2pNmgn8eymW0RIXLIK_FyePUdUTZXHfRn1_ibE.OiRRLcZtoW5JnUQTyJ2dQ8_O6nPuidCR1X7wzPNK1kg&dib_tag=se&keywords=Keyboard+Switches&qid=1791773926&refinements=p_76%3A1249158011&rnid=1249156011&rps=1&s=industrial&sprefix=keyboard+switches%2Cindustrial%2C120&sr=1-2) |
| [PCB](https://cart.jlcpcb.com/quote?spm=jlcpcb.Public.2006) | Need it to connect all parts | 1 | $4.00 | $4.00 | [JLCPCB](https://cart.jlcpcb.com/quote?spm=jlcpcb.Public.2006) |
| [MPU-6050](https://www.amazon.com/kjdElectronics-MPU-6050-Triple-axis-Accelerometer-Gyroscope/dp/B0B2Q3CQG6/ref=sr_1_2?dib=eyJ2IjoiMSJ9.RoHinjlYYq2nUXoWfabvEpzsVtrWuHbtZrpg8TRUC2cozJHUNjlN1HpfDvjQeNJzburRV9Kf2MvFdQG5lXdOR832O3ZvpggMFzrKF3y2fASxmGceeN-F_thlTteDgY3-UTOw2EX5NQu43o0u5p5x8N4jGf1S6fRuuS7eQdFHXs-QOz9CPQklEthY8a3mO-syyvPtNRUgE4McX147o3O-JEaMdwGrd9h9o5-T9Wo7Y2vvAqZ_EQtPT8nGplYkxzycuDU8B8jlERB1xbJVr5V7iOpKn7Ltoil94eKyPsbLgy4.ZC77yDV87lNHts4yztextDVQg05UL--kWViMMpu8-Ts&dib_tag=se&keywords=MPU6050&qid=1791774211&refinements=p_76%3A1249158011&rnid=1249156011&rps=1&s=industrial&sr=1-2) | To know if the starbie is tilted | 1 | $6.29 | $6.29 | [Amazon](https://www.amazon.com/kjdElectronics-MPU-6050-Triple-axis-Accelerometer-Gyroscope/dp/B0B2Q3CQG6/ref=sr_1_2?dib=eyJ2IjoiMSJ9.RoHinjlYYq2nUXoWfabvEpzsVtrWuHbtZrpg8TRUC2cozJHUNjlN1HpfDvjQeNJzburRV9Kf2MvFdQG5lXdOR832O3ZvpggMFzrKF3y2fASxmGceeN-F_thlTteDgY3-UTOw2EX5NQu43o0u5p5x8N4jGf1S6fRuuS7eQdFHXs-QOz9CPQklEthY8a3mO-syyvPtNRUgE4McX147o3O-JEaMdwGrd9h9o5-T9Wo7Y2vvAqZ_EQtPT8nGplYkxzycuDU8B8jlERB1xbJVr5V7iOpKn7Ltoil94eKyPsbLgy4.ZC77yDV87lNHts4yztextDVQg05UL--kWViMMpu8-Ts&dib_tag=se&keywords=MPU6050&qid=1791774211&refinements=p_76%3A1249158011&rnid=1249156011&rps=1&s=industrial&sr=1-2) |
| **Parts subtotal** | — | — | — | **$31.11** | — |
| **Tax & shipping** | — | — | — | **$0.00** | — |
| **Total** | — | — | — | **$31.11** | — |
