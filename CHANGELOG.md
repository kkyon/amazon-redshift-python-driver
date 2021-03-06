Changelog
=========


v2.0.872 (2020-12-14)
---------------------
- Fix(test,datatype): setup/teardown sql script path. [Brooke White]
- Chore(test): ignore InsecureRequestWarning. [Brooke White]
- Test(idp): integration and unit tests for adfs, azure, okta. [Brooke
  White]
- Test(datashare): skip datashare tests for now. [Brooke White]
- Test(datatype): handle data from server. [Brooke White]
- Feat(datatype): support timetz. [Brooke White]
- Feat(datatype): support super. [Brooke White]
- Feat(connection): add ssl_insecure parameter default to True. [Brooke
  White]
- Test(datashare): connection args, cursor metadata methods. [Brooke
  White]
- Feat(connection): add datashare support, disabled by default. [Brooke
  White]
- Docs: remove log args from connection parameter, explain logging
  usage. [Brooke White]
- Fix(logging): remove logging configuration from connect(), suppress
  log stderr output by default. [Brooke White]
- Perf(imports): use lazy-imports for idp plugins. [Brooke White]
- Chore: correct mypy errors. [Brooke White]
- Feat(Connection): add initializer parameter for server protocol
  version, default to extended metadata. [Brooke White]
- Release v2.0.711. [Brooke White]


v2.0.711 (2020-11-25)
---------------------
- Refactor(cursor): use prepared statements in class methods. [Brooke
  White]
- Release v2.0.659. [Brooke White]


v2.0.659 (2020-11-23)
---------------------
- Refactor(integer-datetime): remove datatype conversion functions for
  when server option integer_datetime is disabled. [Brooke White]
- Refactor: clean up setup.py. [Brooke White]
- Docs: update installation instructions to reflect pandas, numpy being
  optional. [Brooke White]
- Test(cursor): skips test using numpy, pandas if not available. [Brooke
  White]
- Refactor(cursor): check pandas, numpy available before use. [Brooke
  White]
- Build: make numpy, pandas optional dependencies unify dependecy list
  in requirements txt. [Brooke White]
- Test(datatype): remove unsupported tests for timetz, time. [Brooke
  White]
- Test(auth): test invalid db_groups vals result in server error.
  [Brooke White]
- Fix(auth): include DbGroups when getting temp credentials from boto.
  [Brooke White]
- Refactor(cursor): extend fetch_dataframe error handling. [Brooke
  White]
- Doc: Fix errors in connection parameter table. Add missing parameters
  to table (#12) [Brooke White]


v2.0.405 (2020-11-05)
---------------------
- Doc: re-word project description (#8) [Brooke White]


v2.0.399 (2020-11-05)
---------------------
- Chore: Add license, usage files and include in whl (#7) [Brooke White]


v2.0.393 (2020-11-05)
---------------------
- Build: set long_description_format_type set to x-rst (#6) [Brooke
  White]


v2.0.389 (2020-11-05)
---------------------
- Build: include README in built dist (#5) [Brooke White]


v2.0.384 (2020-11-04)
---------------------
- Chore: bump boto3, botocore min versions to 1.16.8, 1.19.8 resp (#4)
  [Brooke White]
- Chore: add readme hyperlink to DBAPI2.0 (#3) [Brooke White]
- Chore: init repository. [Brooke White]
- Docs: Add installation instructions and example usage to README.
  [Brooke White]
- Update THIRD_PARTY_LICENSES. [iggarish]
- Update PULL_REQUEST_TEMPLATE.md. [iggarish]
- Create ISSUE_TEMPLATE.md. [iggarish]
- Create THIRD_PARTY_LICENSES. [iggarish]
- Create CHANGELOG.md. [iggarish]
- Create PULL_REQUEST_TEMPLATE.md. [iggarish]
- Added initial content in README file. [ilesh Garish]
- Added initial content in README file. [ilesh Garish]
- Initial code. [ilesh garish]
- Initial commit. [Amazon GitHub Automation]


