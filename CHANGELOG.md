# Changelog

## [Unreleased]

## [1.0.0] - TBD
- CI improvements
- Added changelog
- Added linters (flake8, isort, black)
- Mark wheels not universal
- Many code style improvements
- Fix test `DraggableMPTTAdminTestCase.test_changelist` 
  broken in djangomaster due to 
  (https://code.djangoproject.com/ticket/31080)

## [0.11.0] - 2020-01-18
- Add an 'all' argument to drilldown_tree_for_node (#474)
- Add Chinese (simplified) translations (#700)
- Fix _is_saved fails when pk is 0 (#704)
- Error messages (`.message_user()`) now have an error level
- Fix Logging tree change when using `DraggableMPTTAdmin` (#714)
- Add Django 3.0 ssupport
- Removing deprecated functions for Django 3
- Test matrix improvements

## [0.10.0] - 2019-04-13
- TBD

## [0.9.1] - 2018-08-01
- TBD

## [0.9.0] - 2017-12-09
- Add support for Django 1.11 and 2.0
- Drop unsupported django versions from test matrix (1.9, 1.10)
- Add Danish and Ukrainian translations
- Rollup the last year worth of minor bug fixes

## [0.8.7] - 2016-12-22
- Better support for Django 1.10
- Updated German and French translations
- Add Chinese (traditional), Hungarian and Finnish translations
- Remove tests folder from package (again)

## [0.8.6] - 2016-08-23
- Add support for django 1.10

## [0.8.5] - 2016-07-21
- Numerous bug fixes (#132, #453, #473, #475, #465 , #428)
- Compatibility with django 1.10rc1

## [0.8.4] - 2016-05-03
- build tweaks (#450, #456)
- Update russian translation

## [0.8.3] - 2016-03-01
- Fixed build

## [0.8.2] - 2016-02-28
- Fixes missing static files (javascript, CSS) in the build

## [0.8.1] - 2016-02-26
- Fix issues with `raw_id_fields` in admin.
- New `DraggableMPTTAdmin` admin class that provides drag & drop node moving functionality

## [0.8.0] - 2015-12-20
New features:
- Add support for python 3.5 (dropped 2.6)
- Add support for django 1.9 (dropped 1.4, 1.6, 1.7)
- Add a node_moved signal
- Spanish (Argentina) translation
- `TreeQuerySet.get_cached_trees()`

Fixes etc:
- Much faster `get_queryset_ancestors/descendants`
- Fixed #176 (infinite recursion when using `.only()` / `.defer()`)
- Much improved test coverage

## [0.7.4] - 2015-05-28
- Fixes a regression affecting `TreeManager.get_queryset_ancestors()` (#379)

## [0.7.3] - 2015-05-07
- TBD

## [0.7.2] - 2015-04-19
- TBD

## [0.7.1] - 2015-04-06
- TBD

## [0.7.0] - 2015-04-03
- TBD

## [0.6.1] - 2014-05-23
- TBD

## [0.6.0] - 2013-08-06
- TBD

## [0.5.5] - 2012-12-09
- TBD

## [0.5.4] - 2012-08-22
- TBD

## [0.5.3] - 2012-08-20
- TBD

## [0.5.2] - 2011-11-25
- TBD

## [0.5.1] - 2011-11-04
- TBD

## [0.5.0] - 2011-10-28
- TBD

## [0.4.2] - 2010-11-01
- TBD

## [0.4.1] - 2010-10-07
- TBD

## [0.4.0] - 2010-10-01
- TBD

## [0.3.1] - 2010-09-04
- TBD

## [0.3.0] - 2010-09-02
- TBD

## [0.2.1] - 2008-01-16
- TBD

## [0.2] - 2008-01-16
- TBD

## [0.1] - 2008-01-04
- TBD

[unreleased]: https://github.com/django-mptt/django-mptt/compare/0.11.0...HEAD
[0.11.0]: https://github.com/django-mptt/django-mptt/compare/0.10.0...0.11.0
[0.10.0]: https://github.com/django-mptt/django-mptt/compare/0.9.1...0.10.0
[0.9.1]: https://github.com/django-mptt/django-mptt/compare/0.9.0...0.9.1
[0.9.0]: https://github.com/django-mptt/django-mptt/compare/0.8.7...0.9.0
[0.8.7]: https://github.com/django-mptt/django-mptt/compare/0.8.6...0.8.7
[0.8.6]: https://github.com/django-mptt/django-mptt/compare/0.8.5...0.8.6
[0.8.5]: https://github.com/django-mptt/django-mptt/compare/0.8.4...0.8.5
[0.8.4]: https://github.com/django-mptt/django-mptt/compare/0.8.3...0.8.4
[0.8.3]: https://github.com/django-mptt/django-mptt/compare/0.8.2...0.8.3
[0.8.2]: https://github.com/django-mptt/django-mptt/compare/0.8.1...0.8.2
[0.8.1]: https://github.com/django-mptt/django-mptt/compare/0.8.0...0.8.1
[0.8.0]: https://github.com/django-mptt/django-mptt/compare/0.7.4...0.8.0
[0.7.4]: https://github.com/django-mptt/django-mptt/compare/0.7.3...0.7.4
[0.7.3]: https://github.com/django-mptt/django-mptt/compare/0.7.2...0.7.3
[0.7.2]: https://github.com/django-mptt/django-mptt/compare/0.7.1...0.7.2
[0.7.1]: https://github.com/django-mptt/django-mptt/compare/0.7.0...0.7.1
[0.7.0]: https://github.com/django-mptt/django-mptt/compare/0.6.1...0.7.0
[0.6.1]: https://github.com/django-mptt/django-mptt/compare/0.6.0...0.6.1
[0.6.0]: https://github.com/django-mptt/django-mptt/compare/0.5.5...0.6.0
[0.5.5]: https://github.com/django-mptt/django-mptt/compare/0.5.4...0.5.5
[0.5.4]: https://github.com/django-mptt/django-mptt/compare/0.5.3...0.5.4
[0.5.3]: https://github.com/django-mptt/django-mptt/compare/0.5.2...0.5.3
[0.5.2]: https://github.com/django-mptt/django-mptt/compare/0.5.1...0.5.2
[0.5.1]: https://github.com/django-mptt/django-mptt/compare/0.5.0...0.5.1
[0.5.0]: https://github.com/django-mptt/django-mptt/compare/0.4.2...0.5.0
[0.4.2]: https://github.com/django-mptt/django-mptt/compare/0.4.1...0.4.2
[0.4.1]: https://github.com/django-mptt/django-mptt/compare/0.4.0...0.4.1
[0.4.0]: https://github.com/django-mptt/django-mptt/compare/0.3.1...0.4.0
[0.3.1]: https://github.com/django-mptt/django-mptt/compare/0.3.0...0.3.1
[0.3.0]: https://github.com/django-mptt/django-mptt/compare/8c5e6282bfe966156278f1baea86547a3249b51b...0.3.0
[0.2.1]: https://github.com/django-mptt/django-mptt/compare/b1ff47882489ba9b3e2d39cb600185c8102b426d...8c5e6282bfe966156278f1baea86547a3249b51b
[0.2]: https://github.com/django-mptt/django-mptt/compare/28a6806578806192cea254aa162eee0a9219711f...b1ff47882489ba9b3e2d39cb600185c8102b426d
[0.1]: https://github.com/django-mptt/django-mptt/tree/28a6806578806192cea254aa162eee0a9219711f
