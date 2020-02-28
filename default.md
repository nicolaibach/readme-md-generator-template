# <%= projectName %>

<% if (projectDescription) { -%>
<%= projectDescription %>
<% } -%>
<% if (installCommand) { -%>

## Install

```sh
<%= installCommand %>
```

<% } -%>
<% if (usage) { -%>

## Usage

```sh
<%= usage %>
```

<% } -%>
<% if (testCommand) { -%>

## Run tests

```sh
<%= testCommand %>
```

<% } -%>
<% if (licenseName && licenseUrl) { -%>

## License

This project is [<%= licenseName %>](<%= licenseUrl %>) licensed.
<% } -%>
