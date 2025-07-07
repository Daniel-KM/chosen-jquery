# Fork of Chosen-JQuery

This fork implements to improvements:
- support of languages with diacritics, so filtering with `e` output elements with `é`.
- ordered and draggable list of options: sync <option> DOM order on form submit so server receives values in the displayed order.
- reset css properties on .search-choice-close to prevent breaking <button> close element.
- add css for .search-choice grab cursor and .chosen-sortable-ghost styles.
- add js for added chosen-sortable.js for drag-and-drop reordering of multiselect choices using SortableJs.

Fully functional and used in [Omeka S](https://omeka.org/s) via module [Easy Admin](https://gitlab.com/Daniel-KM/Omeka-S-module-EasyAdmin).

# Chosen

Chosen is a library for making long, unwieldy select boxes more user friendly.

- jQuery support: 1.7+
- Prototype support: 1.7+

For **documentation**, usage, and examples, see:
https://jjj.github.io/chosen/

For **downloads**, see:
https://github.com/jjj/chosen/releases/

### Package managers

To install with npm:

```
npm install chosen-jjj
```

To install with Composer:

```
composer require jjj/chosen
```

### Contributing to this project

We welcome all to participate in making Chosen the best software it can be. The repository is maintained by only a few people, but has accepted contributions from over 50 authors after reviewing hundreds of pull requests related to thousands of issues. You can help reduce the maintainers' workload (and increase your chance of having an accepted contribution to Chosen) by following the
[guidelines for contributing](contributing.md).

* [Bug reports](contributing.md#bugs)
* [Feature requests](contributing.md#features)
* [Pull requests](contributing.md#pull-requests)

### Chosen Credits

- Concept and development by [Patrick Filler](http://patrickfiller.com) for [Harvest](http://getharvest.com/)
- Design and CSS by [Matthew Lettini](http://matthewlettini.com/)
- 1.8.x and earlier maintained by [@pfiller](http://github.com/pfiller), [@kenearley](http://github.com/kenearley), [@stof](http://github.com/stof), [@koenpunt](http://github.com/koenpunt), and [@tjschuck](http://github.com/tjschuck)
- 2.0.x and later maintained by [@JJJ](http://github.com/JJJ) and contributors
- Chosen includes [contributions by many fine folks](https://github.com/harvesthq/chosen/contributors)
