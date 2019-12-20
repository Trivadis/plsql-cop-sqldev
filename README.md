# PL/SQL Cop for SQL Developer

## Introduction

Trivadis PL/SQL Cop for SQL Developer is a free extension to check an editor content for compliance violations of the [Trivadis PL/SQL & SQL Coding Guidelines Version 3.6](https://trivadis.github.io/plsql-and-sql-coding-guidelines/v3.6/).

PL/SQL Cop calculates metrics per PL/SQL unit, such as:

- McCabe’s cyclomatic complexity
- Halstead’s volume
- The maintainability index
- Lines
- Commands (SQL*Plus and SQL)
- Statements (within a PL/SQL unit)
- etc.

And aggregates them on file level.

The results are presented in an additional tabbed panel. One tab shows all guideline violations to quickly navigate to the corresponding code position. The other tab contains a full HTML report, which also may be opened in your external browser.

## Examples

Open an Oracle PL/SQL or SQL script in a SQL Developer editor and press Ctrl-Shift-C to check your code against the Trivadis PL/SQL & SQL guidelines.

![Check](images/tvdcc-sqldev-check.png)

Navigate through the issues using the cursor keys to highlight the related code section in the linked editor.

![Issues](images/tvdcc-sqldev-issues.png)

Dock the PL/SQL Cop output window on your favorite position within SQL Developer and click on the report tab to reveal some additional metrics. Open the report in an external browser to print or save the report.

![Report](images/tvdcc-sqldev-report.png)

## Configure Update Center

Click the “Help” menu and select “Check for Updates…”. Press the “Add” button to register the update center http://update.salvis.com/ . If you have troubles to configure the proxy settings, because your company requires some additional authentication or similar, then I suggest to download PL/SQL Cop for SQL Developer via the “Download” button below and use the “Install From Local File” option.

![Update Center](images/salvis-update-center.png)

## Releases

You find all releases and release information [here](https://github.com/Trivadis/plsql-cop-sqldev/releases).

## Issues
Please file your bug reports, enhancement requests, questions and other support requests within [Github's issue tracker](https://help.github.com/articles/about-issues/).

* [Questions](https://github.com/trivadis/plsql-cop-sqldev/issues?q=is%3Aissue+label%3Aquestion)
* [Open enhancements](https://github.com/trivadis/plsql-cop-sqldev/issues?q=is%3Aopen+is%3Aissue+label%3Aenhancement)
* [Open bugs](https://github.com/trivadis/plsql-cop-sqldev/issues?q=is%3Aopen+is%3Aissue+label%3Abug)
* [Submit new issue](https://github.com/trivadis/plsql-cop-sqldev/issues/new)

## Frequently Asked Questions

see [Frequently Ased Questions](FAQ.md).

## Further Information

Please find further information about PL/SQL Cop on the [Trivadis](https://www.trivadis.com/en/plsql-cop) website.

## License

PL/SQL Cop for SQL Developer is licensed under the Creative Commons Attribution-NonCommercial-NoDerivs 3.0 Unported License. You may obtain a copy of the License at https://creativecommons.org/licenses/by-nc-nd/3.0/.

![CC-BY_NC-ND](images/CC-BY-NC-ND.png)