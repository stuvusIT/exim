# exim

This role configures and installs exim.

## Requirements

This role only needs an apt based system e.g. Ubuntu

## Role Variables
Every section relates to similar named section in a normal [exim configuration](https://www.exim.org/exim-html-current/doc/html/spec_html/index.html).
This is the reason why there is no description for these section.
Every variable should be set to a multiline string.

| Variable                     | Default / Mandatory |
|------------------------------|---------------------|
| `exim_local_section`         | :heavy_check_mark:  |
| `exim_main_section`          | :heavy_check_mark:  |
| `exim_acls_section`          |                     |
| `exim_router_section`        |                     |
| `exim_transport_section`     |                     |
| `exim_authenticator_section` |                     |
| `exim_rewrite_section`       |                     |
| `exim_retry_section`         |                     |

## Example Playbook

Please see the excellent exim documentation on how to fill the sections.

## License

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).


## Author Information

- [Fritz Otlinghaus (Scriptkiddi)](https://github.com/scriptkiddi) _fritz.otlinghaus@stuvus.uni-stuttgart.de_
