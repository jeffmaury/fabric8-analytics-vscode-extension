# Change Log

## 0.0.11 (December 14th, 2018)
* enhancement - add support for muti-root workspaces. See [#4496](https://github.com/openshiftio/openshift.io/issues/4496)
* fixes - removes usage of depreciated rootpath APIs.
* fixes - Show info status messge only first time manifest is open and then show if any CVEs are detected along with minor bug fixes and updates READMEs

## 0.0.10 (November 5th, 2018)
* enhancement - add support for Quickfixes for any CVEs flagged with codeaction. See [#4516](https://github.com/openshiftio/openshift.io/issues/4516)
* enhancement - provide one to command to trigger Dependency Analytics Report for a particular manifest/Application level. See [4518](https://github.com/openshiftio/openshift.io/issues/4518)
* enhancement - add support to show progress along with Info toast when lsp calls complete.

## 0.0.9 (October 27th, 2018)
* enhancement - add support to show progress when language Server is in action. See [#4487](https://github.com/openshiftio/openshift.io/issues/4487).
* enhancement - Show proper status messages for progress for stack report generation, currently it just shows "Generate Application Stack Report". See [#4487](https://github.com/openshiftio/openshift.io/issues/4487).
* Increases test coverage