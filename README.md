
<h1 align="center">Vortex-Deamon</h1>
## Overview
Vortex-Deamon is the Deamon for the Vortex-Panel.

## Installation
1. Clone the repository:
`git clone https://github.com/draco-labes/draco-daemon`

2. go to panel directory:
`cd draco-daemon` 

3. Install dependencies:
`npm install`

4. Configure DracoDaemon:
- Get your Panel's access key from the Hydra panel's config.json file and set it as 'remoteKey'. Do the same for the other way, set your DracoDaemon access key and configure it on the Panel.

4. Start the Daemon:
`node . # or use pm2 to keep it online`

## Configuration
Configuration settings can be adjusted in the `config.json` file. This includes the authentication key for API access.

## Usage
The daemon runs as a background service, interfacing with the Draco Panel for operational commands and status updates. It is not typically interacted with directly by end-users.

## Contributing
Contributions to enhance the functionality or performance of the Draco Daemon are encouraged. Please submit pull requests for any enhancements.

## License
(c) 2025 MJ and contributors. This software is licensed under the InfinityForge License.


## Credits
InfinityForge
NXIGHT
Joy

- Thanks ma4z,ether,achul123,privt
