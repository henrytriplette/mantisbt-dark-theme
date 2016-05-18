# MantisBT Dark Theme

A darker theme for Mantis bug tracking software - [Mantisbt.org](http://mantisbt.org/)

## Installation

1. Copy the css folder into Mantis root folder.
2. Add the following code to the config_inc.php file.

```
$g_css_include_file = "/css/custom/default.css";
```

#### Optional

1. Add the following code to the config_inc.php file for logo and material design colors.

```
# --- Branding ---
$g_window_title			= 'Mantis Bug Tracker';
$g_logo_image			= 'images/mantis_logo_dark.png';
$g_favicon_image		= 'images/favicon.ico';

# --- Status color additions ---

$g_status_colors['new'] = '#ff9800';
$g_status_colors['feedback'] = '#ff5722';
$g_status_colors['acknowledged'] = '#795548';
$g_status_colors['confirmed'] = '#607d8b';
$g_status_colors['assigned'] = '#2196f3';
$g_status_colors['resolving'] = '#e91e63';
$g_status_colors['resolving_standby'] = '#673ab7';
$g_status_colors['readytotest'] = '#cddc39';
$g_status_colors['testing'] = '#8bc34a';
$g_status_colors['resolved'] = '#4caf50';
$g_status_colors['closed'] = '#9e9e9e';
```

### Screenshots

![MantisBT Dark Theme](/screenshots/1.jpg?raw=true "MantisBT Dark Theme")

### TODO

1. Add responsive css?
2. Turn into a plugin?
3. Add screenshots?

### History

2016-5-18: First release

### Credits

TODO: Write credits

### License

TODO: Write license

## Authors

* **Henry Triplette** - *Initial work* - [Twitter](https://twitter.com/henrytriplette)
