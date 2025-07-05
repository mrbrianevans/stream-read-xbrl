<!-- --8<-- [start:intro] -->
# stream-read-xbrl

> This is a fork of https://github.com/uktrade/stream-read-xbrl since that repo has been taken down.
> I copied the files from an outdated fork (arvandhassan/stream-read-xbrl) of the original repo that was still public.
> I've then updated the source code of stream_read_xbrl.py based on the files on https://pypi.org/project/stream-read-xbrl.
> Some packages are out of date causing tests to fail. Needs some work to get these passing again.


Python package to parse [Companies House accounts data](http://download.companieshouse.gov.uk/en_accountsdata.html) in a streaming way. It converts the zipped XBRL format that Companies House supplies into a single data frame of 38 columns.

On a standard laptop with 8 CPU cores it takes approximately 10 seconds to convert a single day of Companies House accounts data. This does not include the time to transfer the data from Companies House.
<!-- --8<-- [end:intro] -->


<!-- --8<-- [start:features] -->
<!-- --8<-- [end:features] -->

---

Visit the [stream-read-xbrl documentation](https://stream-read-xbrl.docs.trade.gov.uk/) for usage instructions.