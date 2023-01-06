![Hardman & Co](https://raw.github.com/copiadigital/hardmanco_widgets/master/images/hardman-co.svg)
# Hardman & Co Research Widgets

To pull your company's research pieces onto your website automatically there are two options:

- JSON endpoint
- Code snippet

### JSON Endpoint
Every Hardman client has a unique ID and can access all of their research reports via a URL with the ID and the number of reports to display as part of the URL query.

`https://hardmanandco.com/wp-json/research/v1/list/[clientID]/?per_page=[numberOfArticles]`

Example:
`https://hardmanandco.com/wp-json/research/v1/list/2691/?per_page=3`

This will return a JSON string for each article in the following format:

```
{
  "title": "The title of the report",
  "date": "DD MMM YYYY",
  "headline": "A longer introduction to the report",
  "permalink": "The direct URL of the report"
}
```

### Code Snippet
If you would prefer to use a drop-in code snippet to achieve the same thing, you can find it in the example folder.

Don't forget to put the correct client ID, provided by Hardman.

### Support
If you need further support please contact [Copia Digital](https://www.copiadigital.com)

![Copia Digital](https://raw.github.com/copiadigital/hardmanco_widgets/master/images/copia.svg)
