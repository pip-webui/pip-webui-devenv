# <img src="https://github.com/pip-webui/pip-webui/raw/master/doc/Logo.png" alt="Pip.WebUI Logo" style="max-width:30%"> <br/> HTML5 UI Framework for Line-of-Business Applications 

![](https://img.shields.io/badge/license-MIT-blue.svg)

Development of complex Line-of-Business (Enteprise) applications is a serious undertaking that may require effort 
of a large group of designers, developers and testers. Typical product line may have multiple applications, 
each comes with tens of pages and dialogs. Enterprise users pay high price for their systems and demand quality 
of free apps they can see on their phones and tablets. But at the scale of large and complex LOB apps
that presents an big challange. Software vendors are looking for efficient ways to build
their applications delivering modern Look & Feel without spending a fortune on design and development. 

One way to save money is to build portable responsive applications that can work on all devices, form-factors and 
operating systems. The most common way to achieve that is to use HTML5 technology that is supported on virtually
any platform. There are lots of good HTML5 frameworks and libraries. They offer basic mechanisms and simple controls.
However, designers and developers have to go a long way from those basic building blocks to create
large and complex Line-of-Business apps.

Pip.WebUI framework offers a set of higher-level primitives to simplify development of LOB apps.
They were put together to implement consistent and rich [User Experience](https://github.com/pip-webui/pip-webui-ux)
following [Google Material](https://material.google.com) design style.

<div style="border: 1px solid #ccc">
  <img src="https://github.com/pip-webui/pip-webui/raw/master/doc/WebUI-0.png" alt="Pip.WebUI Overview" style="display:block;">
</div>

The framework is based on popular [Angular](https://angularjs.org) framework 
and [Angular Material](https://material.angularjs.org/latest) library of web controls. On the top of that
Pip.WebUI provides a set of modules targeted toward LOB application development.

<div style="border: 1px solid #ccc">
  <img src="https://github.com/pip-webui/pip-webui/raw/master/doc/WebUI-1.png" alt="Pip.WebUI Structure" style="display:block;">
</div>

### Pip.WebUI Modules
<table>
<tr><td width="30%"> <a href="https://github.com/pip-webui/pip-webui-tasks">pip-webui-tasks</a> </td><td width="70%"> Gulp build tasks </td></tr>
<tr><td> <a href="https://github.com/pip-webui/pip-webui-lib">pip-webui-lib</a> </td><td> collection of 3rd party libraries other modules depend on </td></tr>
<tr><td> <a href="https://github.com/pip-webui/pip-webui-css">pip-webui-css</a> </td><td> CSS framework to extend Angular Material styles with animations visual effects </td></tr>
<tr><td> <a href="https://github.com/pip-webui/pip-webui-services">pip-webui-services</a> </td><td> non-visual services: localization, error handling, sessions, formatting, and more... </td></tr>
<tr><td> <a href="https://github.com/pip-webui/pip-webui-behaviors">pip-webui-behaviors</a> </td><td> attacable behaviors: infinite scroll, selectable, focusable, drag-and-drop, unsaved changes </td></tr>
<tr><td> <a href="https://github.com/pip-webui/pip-webui-themes">pip-webui-themes</a> </td><td>support for custom color themes </td></tr>
<tr><td> <a href="https://github.com/pip-webui/pip-webui-buttons">pip-webui-buttons</a> </td><td> buttons: fabs, action lists, drilldown lists </td></tr>
<tr><td> <a href="https://github.com/pip-webui/pip-webui-headers">pip-webui-headers</a> </td><td> header styles and controls </td></tr>
<tr><td> <a href="https://github.com/pip-webui/pip-webui-lists">pip-webui-lists</a> </td><td> data list controls: simple, checks, references, tables </td></tr>
<tr><td> <a href="https://github.com/pip-webui/pip-webui-dates">pip-webui-dates</a> </td><td>Controls and services to work with dates and times </td></tr>
<tr><td> <a href="https://github.com/pip-webui/pip-webui-controls">pip-webui-controls</a> </td><td> random controls: color picker, popover, empty state and more... </td></tr>
<tr><td> <a href="https://github.com/pip-webui/pip-webui-landing">pip-webui-landing</a> </td><td> landing page controls </td></tr>
<tr><td> <a href="https://github.com/pip-webui/pip-webui-charts">pip-webui-charts</a> </td><td>Chart controls: line, bar, pie, scatter and others.... </td></tr>
<tr><td> <a href="https://github.com/pip-webui/pip-webui-dialogs">pip-webui-dialogs</a> </td><td> standard dialogs: info, confirmation, options, errors </td></tr>
<tr><td> <a href="https://github.com/pip-webui/pip-webui-layouts">pip-webui-layouts</a> </td><td> application layouts: simple, document, master-detail, tiles, dialog </td></tr>
<tr><td> <a href="https://github.com/pip-webui/pip-webui-split">pip-webui-split</a> </td><td> split layout to organize complex hierarchical content </td></tr>
<tr><td> <a href="https://github.com/pip-webui/pip-webui-nav">pip-webui-nav</a> </td><td> navigation mechanisms: appbar and sidenav </td></tr>
<tr><td> <a href="https://github.com/pip-webui/pip-webui-errors">pip-webui-errors</a> </td><td> error handling pages and controls </td></tr>
<tr><td> <a href="https://github.com/pip-webui/pip-webui-locations">pip-webui-locations</a> </td><td> location controls </td></tr>
<tr><td> <a href="https://github.com/pip-webui/pip-webui-files">pip-webui-files</a> </td><td> file controls </td></tr>
<tr><td> <a href="https://github.com/pip-webui/pip-webui-settings">pip-webui-settings</a> </td><td> extensible settings page </td></tr>
<tr><td> <a href="https://github.com/pip-webui/pip-webui-help">pip-webui-help</a> </td><td> extensible help page </td></tr>
</table>

### Compatibility
 * Browsers: IE11+, Edge, Chrome 47+, Firefox 43, Opera 35
 * OSes: Windows, Windows Phone, MacOS, iOS, Android
 * 3rd Party Libraries: Angular 1.5.5+, Angular Material 1.0.8+

## Learn more about Pip.WebUI

- [Getting started](https://github.com/pip-webui/pip-webui-sample)
- [Online samples](http://webui.pipdevs.com)
- [API documentation](http://webui-api.pipdevs.com)
- [Frequently Asked Questions](https://github.com/pip-webui/pip-webui/wiki/Frequently-Asked-Questions)
- [UX Concept implemented by Pip.WebUI](https://github.com/pip-webui/pip-webui-ux)
- [Pip.WebUI project wiki](https://github.com/pip-webui/pip-webui/wiki)
- [Pip.WebUI discussion forum](https://groups.google.com/forum/#!forum/pip-webui)
- [Pip.WebUI team blog](https://pip-webui.blogspot.com/)
- [Developer's guide](https://github.com/pip-webui/pip-webui/blob/master/doc/DevelopersGuide.md)
- [Contributing to Pip.WebUI](https://github.com/pip-webui/pip-webui/blob/master/doc/ContributorsGuide.md)

## Acknowledgements

This project would not be possible without effort contributed by particular individuals.

- **Sergey Seroukhov** - the project founder, architecture, web development and documentation
- **Mark Zontak** - team management and web development
- **Alex Masliev** - UX concept, interaction and graphical design
- **Anastas Fonotov** - web development
- **Alex Dvoykin** - web development
- **Kate Negrienko** - web development
- **Andrey Podgorniy** - code cleanup and documentation

We also would like to recognize help received from the following companies.

- [**Digital Living Software Corp.**]()
- [**Conceptual Vision Consulting LLC**](http://www.conceptualvisionconsulting.com)
- [**T&I Labs Inc.**](http://www.tilabs.com)
- [**Modular Mining Systems Inc.**](http://www.mmsi.com)
- [**EPAM Systems**](http://www.epam.com)

## License agreement

Pip.WebUI is released under [MIT license](License) and totally free for commercial and non-commercial use.
