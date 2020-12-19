# Domain DNS stage

Please follow through what's available with [configuring an apex domain](https://help.github.com/en/articles/managing-a-custom-domain-for-your-github-pages-site#configuring-an-apex-domain). My approach was to create A records that point to the following IP addresses for GitHub Pages -

```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

Wait for the DNS propogation to take place - can vary somewhere between 5 minutes to 78 hours (or more).

# Dependencies

The setup uses the following third party dependecies (notwithstanding the obvious ones, those of which have been defined under [prerequisites](#prerequisites))

1. [Materialize CSS](https://materializecss.com)
2. [Google fonts](https://fonts.google.com/specimen/Bree+Serif)

# Usage

Once you have everything setup, you can then navigate to your domain (in this case, https://reurl.io/) and -

1. Fill in the destination (long) URL that you'd want a user to land on
2. Provide a slug (short notation) that would go right after your domain name
3. Hit `Enter` or click **CREATE**

# App Script

[View code](https://github.com/nguyenthephuc/apps-script/tree/main/reurl.io) (Private)

# Source
This project is a development version on https://github.com/schoraria911/gas-url-shortener
