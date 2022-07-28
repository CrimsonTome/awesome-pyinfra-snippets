# awesome-pyinfra-snippets

> A list of awesome snippets to use with [Pyinfra](https://pyinfra.com/).

## System Requirements

- Python 3 + pip
- [pipx](https://pypa.github.io/pipx/installation/)
- Linux (Windows may work but is untested)

## Getting Started

- `pipx install pyinfra`
- (strongly recommended) have a valid SSH config file with your SSH keys added to any target machines with `ssh-copy-id` - snippets in this repo will likely assume you have one

### To Run

To run snippets: `pyinfra target-or-target-file path/to/snippet.py`

TODO: add example

## Snippets

Snippets can be found in the [snippets](/snippets) folder. See also examples from the [official repo](https://github.com/Fizzadar/pyinfra/tree/2.x/examples)

## Disclaimers

- I (CrimsonTome) will not be held liable for any damages made to systems executing these scripts. You are always advised to look before you run anything. If you don't understand something: 
  - look it up
  - read the [docs](docs.pyinfra.com/)
  - or just don't run it

This list has no affiliation with the [awesome lists](https://github.com/sindresorhus/awesome) as it would not meet the guidelines because this is more of a code snippet list than a resource list with lots of links. As such this repo cannot be Awesome certified.

## License 

awesome-pyinfra-snippets is released under the MIT license. The full license text is included in the [LICENSE](/LICENSE) file in this repository. Tldr legal have a [great summary](https://tldrlegal.com/license/mit-license) of the license if you're interested.
