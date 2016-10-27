# HTML emails with MJML

[MJML](https://mjml.io/documentation/) is "a markup language designed to reduce the pain of coding a responsive email." It uses XML to abstract the convoluted HTML that's required by the wide variety of email clients.


## Install

To run locally install mjml

```
npm install -g mjml
```

More information on the [mjml download page](https://mjml.io/download)


## Usage

To convert mjml to HTML:

```
mjml -r template/filename.mjml -o dist/filename.html
```

See [mjml documentation](https://mjml.io/documentation/) for available tags and options.
