0.7.0 UNRELEASED
----------------

- Move ``TTLCache.ExpiredError`` to module level.

- Refactor ``LRUCache``, ``TTLCache``.

- Remove ``NullContext`` implementation based on ``ExitStack``.

- Rename `Changes` to `CHANGES.rst`.


0.6.0 2014-10-13
----------------

- Raise ``TTLCache.ExpiredError`` for expired ``TTLCache`` items.

- Support unsynchronized function decorators.

- Allow ``@cachedmethod.cache()`` to return None


0.5.1 2014-09-25
----------------

- No formatting of ``KeyError`` arguments.

- Update ``README.rst``.


0.5.0 2014-09-23
----------------

- Do not delete expired items in TTLCache.__getitem__().

- Add ``@ttl_cache`` function decorator.

- Fix public ``getsizeof()`` usage.


0.4.0 2014-06-16
----------------

- Add ``TTLCache``.

- Add ``Cache`` base class.

- Remove ``@cachedmethod`` `lock` parameter.


0.3.1 2014-05-07
----------------

- Add proper locking for ``cache_clear()`` and ``cache_info()``.

- Report `size` in ``cache_info()``.


0.3.0 2014-05-06
----------------

- Remove ``@cache`` decorator.

- Add ``size``, ``getsizeof`` members.

- Add ``@cachedmethod`` decorator.


0.2.0 2014-04-02
----------------

- Add ``@cache`` decorator.

- Update documentation.


0.1.0 2014-03-27
----------------

- Initial release.