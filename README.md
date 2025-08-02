# mac.bash

Ever seen your friend's `.DS_Store` files pushed to github and thought, "wow, I wish I could have that too?" With `mac.bash`, you can emulate the most important functionality of macos right in your linux shell.

Every time you `cd` into a directory, `mac.bash` has a small chance of writing a `.DS_Store` file, containing some lovely ascii art.

To install, just clone this repository and add `source macos` to your `.bashrc`. (perhaps i'll figure out how to package this for actual distros later, `apt install macos` would be pretty funny)

Critically acclaimed:

> "The most disruptive technology of our time"

> "Apple doesn't innovate anymore, but this guy does"

## Roadmap

- [x] .DS_Store functionality
- [ ] violate court orders
- [ ] blazingly fast `.DS_Store` remover (rust btw), because I accidentally left this on and now the tim cook asciis are filling up my disk
- [ ] nixos module
