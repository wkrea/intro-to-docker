# An introduction to Docker

This is material for REA's internal introductory Docker training.

The slide-deck is implemented in HTML and Javascript, so is
easy to run in any browser.  Open `index.html` to start.

If you are digesting this material as part of organised training,
we recommend running through the setup process *before* you turn
up on the day:

1. Install Docker and Docker Compose

  - [Docker for Mac](https://docs.docker.com/docker-for-mac/) is a good option.

or

  ```
  brew tap caskroom/cask
  brew cask install docker
  ```

2. Clone this repository

  ```
  git clone https://github.com/realestate-com-au/intro-to-docker.git
  ```

3. Run `./setup.sh` (estimated download size is 1.5GB)

  ```
  $ ./setup.sh
  YAY: /var/run/docker.sock exists
  YAY: I can talk to docker

  Docker is at localhost

  YAY: docker version 1.12.0
  YAY: docker-compose version 1.8.0

  Pulling some images to get you started ...
  ```

4. You can then open the slides from your local copy:

```
open index.html
```
