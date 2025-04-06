+++
date = '2020-08-25T02:17:00+01:00'
draft = false
title = 'GSoC Wikimedia Bi-Weekly Report 8'
categories = ['Google Summer of Code 2020']
+++

(This is part of a (mandatory) blog series documenting my experience in GSoC 2020 with Wikimedia Foundation. This series should serve for record-keeping purposes and as a reference for future GSoC students.)

## Added: More Test Questions

To prepare the tool for public usage, more test questions were added to make sure that users have test questions to answer when using the tool.

## Added: Ability to Post Edits to Wikimedia Commons

One of the most important function of the tool is the ability to post edits to Wikimedia Commons. We’ve added the ability to post depict claims and depict prominence edits to the site.

## GSoC Coming to an End

I’ll publish another separate blog post documenting this whole program.

## Final Report for this Project

(this section is copied over form https://phabricator.wikimedia.org/T261179, refer to the task on Phabricator for the most updated version of the report)

**Summary**  
A tool, Media Data Verification Tool (MDVT) was created under this program, which allows users to verify image data, mainly depict statement and qualifiers, on Wikimedia Commons.

**Code Changes**  
During the development process, we decided to work on GitHub before the tool becomes stable and get transferred to Gerrit.  
Link to the repository on GitHub: [https://github.com/gabrielchl/media-data-verification-tool](https://github.com/gabrielchl/media-data-verification-tool)  
Below is a list of key commits:

|Commit|Summary|
|--|--|
|[6d4b89d](https://github.com/gabrielchl/media-data-verification-tool/commit/6d4b89dfe62ad57b23a8932a42b2b40a02eed7d7)|First commit|
|[5ad717a](https://github.com/gabrielchl/media-data-verification-tool/commit/5ad717accb8dc09c74125af61444ee3b74650429)|Last commit before project proposal submission|
|[4c8be75](https://github.com/gabrielchl/media-data-verification-tool/commit/4c8be7598d6767e9c8448e444edd5f9c92bfad7d)|Save user answers on the server|
|[f773d3d](https://github.com/gabrielchl/media-data-verification-tool/commit/f773d3d690fef84af6fade0e2c85d6c72f3a83bf)|Added test questions|
|[55b6d86](https://github.com/gabrielchl/media-data-verification-tool/commit/55b6d860c7ef57a1f0af5b82fdb03ed4086f98b4)|Added user contribution profile page|
|[1fc083e](https://github.com/gabrielchl/media-data-verification-tool/commit/1fc083e7cd43e596dade2ddb3cca66ab09d09b5c)|Added prominence question|
|[c351d06](https://github.com/gabrielchl/media-data-verification-tool/commit/c351d06ec4bb93c72e0d37de68c4a327383649b1)|Added depict qualifiers question|
|[50cded4](https://github.com/gabrielchl/media-data-verification-tool/commit/50cded4257333dc18a361df976a40e7a1bd498ac)|Added public api to query user and contribution data|
|[18ab7f0](https://github.com/gabrielchl/media-data-verification-tool/commit/18ab7f04e600ef26174f6312b5694fe1f3ac5f5c)|Added unit test|
|[a6067c9](https://github.com/gabrielchl/media-data-verification-tool/commit/a6067c95320d87d6ad48969d00236c51f8ba922d)|i18n|
|[1afaa36](https://github.com/gabrielchl/media-data-verification-tool/commit/1afaa365e04e2ec6ea46a93d0f3ab76c20c6011b), [f4741f9](https://github.com/gabrielchl/media-data-verification-tool/commit/f4741f9c4b6c838724a611445cab7a51c095f3c4)|Publish edits to commons|

**Next Steps**  
Despite the end of the program, we (me and my mentors) will continue working on completing the tool, which includes but isn’t limited to adding the following features:

- Linkage with ISA
- Ability to publish qualifier edits to Commons
