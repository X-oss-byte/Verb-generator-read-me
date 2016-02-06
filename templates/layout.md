# {%= name %} {%= badge('npm') %} {%= badge('travis') %}

> {%= description %}

## Install
{%= include('install-npm', {save: true}) %}

{% body %}

## Running tests
{%= include("tests") %}

## Related projects
{%= related(verb.related.list) %}

## Contributing
{%= include("contributing") %}

## Author
{%= include("author") %}

## License
{%= copyright({linkify: true}) %}
{%= license %}

***

{%= include("footer") %}

{%= reflinks(verb.reflinks) %}
