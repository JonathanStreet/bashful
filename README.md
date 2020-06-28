# bashful

> adjective: bashful
> \
> &nbsp; &nbsp; &nbsp; &nbsp; *reluctant to draw attention to oneself; shy.*

*Bashful* is a static site generator.

Its aim is to provide a straightforward static site generator that has a minimal footprint and dependencies, whilst being capable of generating a functional website.

Coming soon™.

## Usage

Download the code from this repository.
```
git clone https://github.com/JonathanStreet/bashful.git
```

Install `bashful` to your local bin folder.
<sup>*Coming soon™</sup>
```
make install
```


Prepare the directory for your website, the following structure is suggested:
```
blog
├── generated
└── source
    ├── <file>.md
    ├── css
    │   └── <css files>
    ├── fonts
    │   └── <fonts>
    ├── img
    │   └── <images>
    ├── index.md
    ├── p
    │   ├── <blog posts>
    │   └── YYY-MM-DD-url-slug.md
    └── templates
        └── <pandoc-template>
```
### Configuration

Modifications to the script can be made directly for configuration.

*Upcoming-feature* - Utilse a `.bashfulrc` file which contains variables sourced by the script (override the default hard-coded values).
<sup>*Coming soon™</sup>

*Upcoming-feature* - Introduce a sub-command (e.g. `bashful init`) which generates the required source code for an example website / initialisation of `.bashfulrc` with prompts.
<sup>*Coming soon™</sup> 

### Generate

Run `bashful` on your blog directory.

<sup>\*Note: you  must define the `source` & `destination` directories so the script can identify what to run.</sup>

## Features
TBC

## Changelog
* `v0.1.0-rc` - Initial submission of `bashful` script.

## License
Copyright &copy; 2020 Jonathan Street. All rights reserved.
