=======
Changes
=======


1.2 (2018-10-26)
----------------

- Dropped ``requests`` library in favor of using ``aiohttp`` for both sync and async interfaces.


1.1 (2018-10-25)
----------------

- Renamed all ``station_id`` method parameters to ``station``, possibly breaking your code.
- This argument can now handle an entire station dictionary, and will extract the station_id automatically.


1.0 (2018-10-24)
----------------

- Initial PyPI release. 🎉
