# Debtors
https://debtors.pedromoleitao.com

The Portuguese Tax Authority holds a list of all of it's debtors, from singular individuals to colective entities here:

https://static.portaldasfinancas.gov.pt/app/devedores_static/de-devedores.html

This information is presented in a set of PDFs, making it hard to search, analyse or actually find someone in it.

This app displays this data in an interactive table with search, filtering and exporting (csv) functionalities.

It reads from a JSON file, updated daily and generated by the python scraper in [here](https://github.com/oleitao/debtors-scraper).

The entire platform runs free of charge, using github actions to update the backend service, github to serve the json data and cloudflare pages to host the frontend.

## Contributing

Contributions are welcome. Feel free to open an issue or submit a pull request. If you're not sure where to start, mention me in the comments!

## Local setup

### Instal dependencies

```
npm install
```

### Compiles and hot-reloads for development

```
npm run dev
```

### Compiles and minifies for production

```
npm run build
```
