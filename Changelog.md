### Changelog

All notable changes to this project will be documented in this file. Dates are displayed in UTC.

Generated by [`auto-changelog`](https://github.com/CookPete/auto-changelog).

#### [v9.3.2](https://github.com/TeselaGen/ve-sequence-parsers/compare/v9.3.1...v9.3.2)

- adding .prot snapgene file parsing [`d9e86d7`](https://github.com/TeselaGen/ve-sequence-parsers/commit/d9e86d7e3fce590a8d3bfce293db262d500c857c)
- publishing new patch [`64da55c`](https://github.com/TeselaGen/ve-sequence-parsers/commit/64da55cd722d21688ec283729df3151a852dd976)
- tiny copy fix [`2b6c8aa`](https://github.com/TeselaGen/ve-sequence-parsers/commit/2b6c8aa0b0b015a879152991c535b0275ab9e0b4)

#### [v9.3.1](https://github.com/TeselaGen/ve-sequence-parsers/compare/v9.3.0...v9.3.1)

> 24 February 2023

- publishing new minor [`edec4f5`](https://github.com/TeselaGen/ve-sequence-parsers/commit/edec4f53901514ec67c690b5f953200a5d554c7f)
- updating gp|genpep parsing logic [`2bf2372`](https://github.com/TeselaGen/ve-sequence-parsers/commit/2bf2372196417ac2b037e685d82ed9ada49c68ae)

#### [v9.3.0](https://github.com/TeselaGen/ve-sequence-parsers/compare/v9.2.1...v9.3.0)

> 13 February 2023

- adding geneious parsing [`0a88d06`](https://github.com/TeselaGen/ve-sequence-parsers/commit/0a88d061708916f1415eabf2ca1a8f1110245859)
- publishing new patch [`9df36e3`](https://github.com/TeselaGen/ve-sequence-parsers/commit/9df36e3f66b49e030aa0c46e7a40b0b4c7ef330a)

#### [v9.2.1](https://github.com/TeselaGen/ve-sequence-parsers/compare/v9.2.0...v9.2.1)

> 27 January 2023

- Added json to json function from OVE [`#238`](https://github.com/TeselaGen/ve-sequence-parsers/pull/238)
- added json to json function [`f564e38`](https://github.com/TeselaGen/ve-sequence-parsers/commit/f564e382ccdd3cb049380dc9cab1ae6c08d95c2b)
- Updated jsonToJsonString naming and fixed export [`4857492`](https://github.com/TeselaGen/ve-sequence-parsers/commit/4857492b4954a54adc36b9f025dfff8676a547cf)
- improved jsonToJson tests [`a1bf50b`](https://github.com/TeselaGen/ve-sequence-parsers/commit/a1bf50b925ab874ab39d10b04da919ddbcb9b9d1)

#### [v9.2.0](https://github.com/TeselaGen/ve-sequence-parsers/compare/v9.1.0...v9.2.0)

> 18 January 2023

- Adds digest part fields to genbank notes [`#237`](https://github.com/TeselaGen/ve-sequence-parsers/pull/237)
- stripping URLs from fasta/json files by default, adding option to mangleUrls or to not do any stripping/mangling [`9a65171`](https://github.com/TeselaGen/ve-sequence-parsers/commit/9a651716f2856b2921f95bdb1cbe9d7ad016d40b)
- moves global var outta fn [`f71f466`](https://github.com/TeselaGen/ve-sequence-parsers/commit/f71f466df8d0deb5c2d9efd14f9cfe5319bfddae)
- avois custom formatting [`15ab7cd`](https://github.com/TeselaGen/ve-sequence-parsers/commit/15ab7cd81016614315f9a4a0406470c6c7910fc1)

#### [v9.1.0](https://github.com/TeselaGen/ve-sequence-parsers/compare/v9.0.1...v9.1.0)

> 6 January 2023

- adding mangling and unmangling to URLs by default when converting to/from fasta/gb [`023fc1b`](https://github.com/TeselaGen/ve-sequence-parsers/commit/023fc1b3af35ce0b84f65f20876621417189450f)
- publishing new patch [`af5e959`](https://github.com/TeselaGen/ve-sequence-parsers/commit/af5e95915f270088a2d123fad84b55ef07e7aba7)

#### [v9.0.1](https://github.com/TeselaGen/ve-sequence-parsers/compare/v9.0.0...v9.0.1)

> 14 November 2022

- publishing new major [`a21fe72`](https://github.com/TeselaGen/ve-sequence-parsers/commit/a21fe72444b742d5d5a75d9a7d9fdb050313f875)
- updating validateSequence to also set falsy feature types to misc_feature [`114a80a`](https://github.com/TeselaGen/ve-sequence-parsers/commit/114a80addda95252ab4eeada0e0ec77a96026dcc)

### [v9.0.0](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.32...v9.0.0)

> 14 November 2022

- updating to add a new coerceFeatureTypes flag [`bc7811a`](https://github.com/TeselaGen/ve-sequence-parsers/commit/bc7811a32ac8077d34d25e19265a21b8f10383a8)
- publishing new patch [`4e4aded`](https://github.com/TeselaGen/ve-sequence-parsers/commit/4e4adedd843fd9133585129aa04679195efc04d5)

#### [v8.3.32](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.31...v8.3.32)

> 27 September 2022

- 'n' should be a string before call n.toLowerCase() [`#231`](https://github.com/TeselaGen/ve-sequence-parsers/pull/231)
- add test [`5fc05eb`](https://github.com/TeselaGen/ve-sequence-parsers/commit/5fc05eb20223241d4088ff9be6272301a9a75db0)
- publishing new patch [`97aa93b`](https://github.com/TeselaGen/ve-sequence-parsers/commit/97aa93b125892343c2709e59d719237bd479e54d)
- Update validateSequence.js [`8aedc4f`](https://github.com/TeselaGen/ve-sequence-parsers/commit/8aedc4f3eec8d6f66172165c22f853c68ea5e89d)

#### [v8.3.31](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.30...v8.3.31)

> 16 August 2022

- updating anyToJson to handle auto parsing in of teselagen JSON files [`43cbdef`](https://github.com/TeselaGen/ve-sequence-parsers/commit/43cbdef0407b0acd2fe7445e7de0666d0bafa74d)
- publishing new patch [`95d0e45`](https://github.com/TeselaGen/ve-sequence-parsers/commit/95d0e452d3cb1beb1c22e0f0ff0efd400cc234e9)

#### [v8.3.30](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.29...v8.3.30)

> 4 August 2022

- updating to remove xml2Js with fast-xml-parser [`5b3a51e`](https://github.com/TeselaGen/ve-sequence-parsers/commit/5b3a51e9291a4884b59a9af6af363ba0ef854862)
- publishing new patch [`e754d97`](https://github.com/TeselaGen/ve-sequence-parsers/commit/e754d973454ddfbfd45875b16a2163d89796cb48)
- tiny [`e9b4ed5`](https://github.com/TeselaGen/ve-sequence-parsers/commit/e9b4ed511d3c6d11b0e2d642ce85b81dc5b05a06)

#### [v8.3.29](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.28...v8.3.29)

> 29 July 2022

- adding an arrowheadType value to hold genbank 'direction' information [`dd24abe`](https://github.com/TeselaGen/ve-sequence-parsers/commit/dd24abe57f140f6cd233c7e3f1f65ad1cf1fdbf3)
- publishing new patch [`76adb12`](https://github.com/TeselaGen/ve-sequence-parsers/commit/76adb1259df12655ded7e087883bc5a1d6d4cdc1)

#### [v8.3.28](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.27...v8.3.28)

> 14 July 2022

- update more codes [`c87c22e`](https://github.com/TeselaGen/ve-sequence-parsers/commit/c87c22ef368b3e18f2420eba5314d50b3d0c9856)
- treat circularityExplicitlyDefined as an option to the parser [`08ace7c`](https://github.com/TeselaGen/ve-sequence-parsers/commit/08ace7c2360ea628e5c37219de074c64ad3009ae)
- minor tweaks [`bbc71bb`](https://github.com/TeselaGen/ve-sequence-parsers/commit/bbc71bb59e4bc96a2e0c29923090823bf3436521)

#### [v8.3.27](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.25...v8.3.27)

> 17 June 2022

- package.json and nvmrc [`#227`](https://github.com/TeselaGen/ve-sequence-parsers/pull/227)
- Add accession in genbankToJson and in test [`833e4cd`](https://github.com/TeselaGen/ve-sequence-parsers/commit/833e4cd9be511f66e4f97b083cb15da905cb83d6)
- updating yarn lock [`9c4b6a9`](https://github.com/TeselaGen/ve-sequence-parsers/commit/9c4b6a978e9bbead8b4d22f55a278587cd780517)
- Update README.md [`ddd81d8`](https://github.com/TeselaGen/ve-sequence-parsers/commit/ddd81d8c5d31e73c609c48e3e74127c0f57c4adc)

#### [v8.3.25](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.24...v8.3.25)

> 10 March 2022

- Add support for unparsed names (close #185) [`#224`](https://github.com/TeselaGen/ve-sequence-parsers/pull/224)
- Merge pull request #224 from Benjamin-Lee/master [`#185`](https://github.com/TeselaGen/ve-sequence-parsers/issues/185)
- Add support for unparsed names (close #185) [`#185`](https://github.com/TeselaGen/ve-sequence-parsers/issues/185)
- publishing new patch [`f7de14d`](https://github.com/TeselaGen/ve-sequence-parsers/commit/f7de14d5adc7745bb5e4f3837ad0be9b4e9ec607)
- removing prepublishOnly in favor of prepare [`37c6a80`](https://github.com/TeselaGen/ve-sequence-parsers/commit/37c6a802fa2f79e07e349e6794f169e3b1dcb06e)

#### [v8.3.24](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.23...v8.3.24)

> 4 March 2022

- publishing new patch [`877bed5`](https://github.com/TeselaGen/ve-sequence-parsers/commit/877bed567955be71f96f6fc3f2e75f3c1afeda1b)
- trying to fix non-updating releases [`04e493c`](https://github.com/TeselaGen/ve-sequence-parsers/commit/04e493c2ec256d3b360fd52e478938be87cacd6d)

#### [v8.3.23](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.22...v8.3.23)

> 4 March 2022

- publishing new patch [`0bff809`](https://github.com/TeselaGen/ve-sequence-parsers/commit/0bff80992f0b29f6a3e9928c88b2c1d0cc697525)
- trying to fix non-updating releases [`ac05f96`](https://github.com/TeselaGen/ve-sequence-parsers/commit/ac05f9630c4118c5648402e049a55910b18f1802)

#### [v8.3.22](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.21...v8.3.22)

> 23 February 2022

- adding support for .bases and .primerBindsOn properties on primers [`675f8f2`](https://github.com/TeselaGen/ve-sequence-parsers/commit/675f8f2da44136f76a32ed775b97b858b8eb285c)
- publishing new patch [`9820009`](https://github.com/TeselaGen/ve-sequence-parsers/commit/9820009082b7678b8a7eedb25d1e5f7fb46bbb27)

#### [v8.3.21](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.20...v8.3.21)

> 25 January 2022

- updating jsonToGenbank to make sure there is always a space at the 68 position [`9a9ba5b`](https://github.com/TeselaGen/ve-sequence-parsers/commit/9a9ba5ba5a3b88f06e17d335e47fffe5df9ba2c4)
- publishing new patch [`b3ddd77`](https://github.com/TeselaGen/ve-sequence-parsers/commit/b3ddd770c2944baef3e8625a2347fb63c72dba1e)
- updating repo path [`8a3f7bb`](https://github.com/TeselaGen/ve-sequence-parsers/commit/8a3f7bb219f87440041403eb08234c210bbd6d1c)

#### [v8.3.20](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.19...v8.3.20)

> 9 November 2021

- publishing new patch [`1290f23`](https://github.com/TeselaGen/ve-sequence-parsers/commit/1290f23eb8565cdbdbbc3d46e675221a2447a109)
- exporting convertBasePosTraceToPerBpTrace as a top level function [`81520f2`](https://github.com/TeselaGen/ve-sequence-parsers/commit/81520f2496eca1c0a568562db9829635494444d9)

#### [v8.3.19](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.18...v8.3.19)

> 3 November 2021

- updating ab1 parser to include a per base pair trace [`22ac977`](https://github.com/TeselaGen/ve-sequence-parsers/commit/22ac977d01b4776bc5dd43a42e7875594a634ba5)
- publishing new patch [`d36b49b`](https://github.com/TeselaGen/ve-sequence-parsers/commit/d36b49b08c8c54a32d1ae92e195c41736e5e6225)

#### [v8.3.18](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.17...v8.3.18)

> 13 October 2021

- updating npmignore [`cb5e479`](https://github.com/TeselaGen/ve-sequence-parsers/commit/cb5e479124465f00b28e87cd55d3af72e7af3a24)
- publishing new patch [`6ddfad4`](https://github.com/TeselaGen/ve-sequence-parsers/commit/6ddfad4b80aed3106d456ccd91a00fc92a0f35b8)

#### [v8.3.17](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.16...v8.3.17)

> 12 October 2021

- updating ab1ToJson to remove qualNums if that data is missing/corrupted [`f046dea`](https://github.com/TeselaGen/ve-sequence-parsers/commit/f046dea067f791dd3d10124685c6dfddebc5a472)
- publishing new patch [`9b501d5`](https://github.com/TeselaGen/ve-sequence-parsers/commit/9b501d5e21555cb3896176497f980be0894a8533)

#### [v8.3.16](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.15...v8.3.16)

> 16 August 2021

- publishing new patch [`174d529`](https://github.com/TeselaGen/ve-sequence-parsers/commit/174d52905ba43ffa698fc21d3cba89ac88b0893b)
- adding support for import/export of annotations with overlapsSelf=true [`541412b`](https://github.com/TeselaGen/ve-sequence-parsers/commit/541412b673f819c16a8f0ad0f4db1e3125255fe2)

#### [v8.3.15](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.14...v8.3.15)

> 16 August 2021

- adding support for import/export of annotations with overlapsSelf=true [`15ed418`](https://github.com/TeselaGen/ve-sequence-parsers/commit/15ed418780683c54402269a8d778d8e20c199a6e)
- Merge pull request #216 from TeselaGen/dependabot/npm_and_yarn/tar-4.4.15 [`1dc4980`](https://github.com/TeselaGen/ve-sequence-parsers/commit/1dc498040c65bb8a51b8eee29b8b4000c952254c)
- [Security] Bump tar from 4.4.10 to 4.4.15 [`6cb660f`](https://github.com/TeselaGen/ve-sequence-parsers/commit/6cb660fcbbccb5df0205e68ec07c812cf1161213)

#### [v8.3.14](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.13...v8.3.14)

> 22 July 2021

- Pr/thomas1664/105 [`#188`](https://github.com/TeselaGen/ve-sequence-parsers/pull/188)
- adding an allowOverflowAnnotations to parsers [`b2b11f7`](https://github.com/TeselaGen/ve-sequence-parsers/commit/b2b11f780a29ac904faef09a3aba6badfad7081f)
- Merge pull request #209 from TeselaGen/dependabot/npm_and_yarn/elliptic-6.5.4 [`6f46387`](https://github.com/TeselaGen/ve-sequence-parsers/commit/6f463877e74ec529186a62a630c120599d29cad7)
- [Security] Bump elliptic from 6.5.1 to 6.5.4 [`0d0b7f7`](https://github.com/TeselaGen/ve-sequence-parsers/commit/0d0b7f742c462dfbda854340cc62ffcf890a897f)

#### [v8.3.13](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.12...v8.3.13)

> 10 June 2021

- updating end of line gb parsing and adding test case from https://github.com/TeselaGen/ve-sequence-parsers/pull/162 [`901ef57`](https://github.com/TeselaGen/ve-sequence-parsers/commit/901ef57ed1a43fc1bc9939b323a8e06428e4c8ca)
- refactor: improved previous fix and added tests [`c69eebf`](https://github.com/TeselaGen/ve-sequence-parsers/commit/c69eebfe5dead59aef2fe97bbb9527230137fff8)
- refactor: removed redundant test [`4d1ff15`](https://github.com/TeselaGen/ve-sequence-parsers/commit/4d1ff151a4fc1d0fffa2b0ec8cd34b29cd45a236)

#### [v8.3.12](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.11...v8.3.12)

> 9 June 2021

- adding a umd example to the readme and updating the validation function slightly [`849b802`](https://github.com/TeselaGen/ve-sequence-parsers/commit/849b802f4307926d6788b79d290a9a32a0aa55ef)

#### [v8.3.11](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.10...v8.3.11)

> 1 June 2021

- removing errant console [`5de90ab`](https://github.com/TeselaGen/ve-sequence-parsers/commit/5de90ab7d33628a7319f649c719b6d4a91b26f69)

#### [v8.3.10](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.6...v8.3.10)

> 28 May 2021

- keep casing, add back in oligo option [`791bb96`](https://github.com/TeselaGen/ve-sequence-parsers/commit/791bb96f9f64aac1c96101d8414044fc3df6559f)
- fix genbank DEFINITION parsing to handle new lines + test [`ac7ffa2`](https://github.com/TeselaGen/ve-sequence-parsers/commit/ac7ffa231eeac4888575657c5332ae0e361512a4)
- Do not create uracil features. Always change u's to t's [`6cc7c0f`](https://github.com/TeselaGen/ve-sequence-parsers/commit/6cc7c0fd2b9016240478850b285f782e3517f79a)

#### [v8.3.6](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.5...v8.3.6)

> 10 May 2021

- updating jsonToFasta to better handle isProtein option [`a733821`](https://github.com/TeselaGen/ve-sequence-parsers/commit/a7338217b29890243493f51514fb16cce53f8291)
- Merge pull request #178 from TeselaGen/dependabot/npm_and_yarn/hosted-git-info-2.8.9 [`b41cfec`](https://github.com/TeselaGen/ve-sequence-parsers/commit/b41cfec1ded1bdf1e7815c6f1a1b17424f26fe10)
- [Security] Bump hosted-git-info from 2.8.4 to 2.8.9 [`ab7424e`](https://github.com/TeselaGen/ve-sequence-parsers/commit/ab7424e30992a7019b60016bcfee4a0566e387eb)

#### [v8.3.5](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.4...v8.3.5)

> 13 April 2021

- fixing logical error in longestFeatureTypeLength calculation [`6b7a624`](https://github.com/TeselaGen/ve-sequence-parsers/commit/6b7a6242d4f97a3a96df176033dafad6aa5a6666)

#### [v8.3.4](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.3...v8.3.4)

> 13 April 2021

- fixing jsonToGenbank to coerce primers with type 'primer' to type 'primer_bind' [`06e5424`](https://github.com/TeselaGen/ve-sequence-parsers/commit/06e5424043d9061fcb13360bc672a6d08c81e59a)

#### [v8.3.3](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.3.0...v8.3.3)

> 13 April 2021

- Rename primer features to primer_bind on export [`ebc286e`](https://github.com/TeselaGen/ve-sequence-parsers/commit/ebc286e923a47c2ab91a90ad699e023548777d84)
- Fix isBrowser logic [`51e1e9d`](https://github.com/TeselaGen/ve-sequence-parsers/commit/51e1e9d5771c0c5590141a110a1bfd18aa4e79a9)

#### [v8.3.0](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.2.0...v8.3.0)

> 2 April 2021

- making getUtf8StringFromFile work in a node env; removing ability to be able to parse gff or sbol without specifying a fileName (for the file extension) [`4771a20`](https://github.com/TeselaGen/ve-sequence-parsers/commit/4771a200d2ca563e99c74a8a93c8e0445b10b52c)

#### [v8.2.0](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.1.0...v8.2.0)

> 1 April 2021

- improving robustness of nodejs arraybuffer parsing [`1d461d7`](https://github.com/TeselaGen/ve-sequence-parsers/commit/1d461d76104661e7805db099ea4ae15310bd5a64)

#### [v8.1.0](https://github.com/TeselaGen/ve-sequence-parsers/compare/v8.0.0...v8.1.0)

> 31 March 2021

- updating snapgeneToJson to follow same format as other parsers and not throw an error but instead just return a non-successful result [`6039a3d`](https://github.com/TeselaGen/ve-sequence-parsers/commit/6039a3d25973bae729a41f827fec8189b49c9a16)

### [v8.0.0](https://github.com/TeselaGen/ve-sequence-parsers/compare/v7.0.13...v8.0.0)

> 31 March 2021

- removing callback style functions; only async/await and promises supported now [`c04762f`](https://github.com/TeselaGen/ve-sequence-parsers/commit/c04762f122e909a43d5283451a335d97fce35368)

#### [v7.0.13](https://github.com/TeselaGen/ve-sequence-parsers/compare/v7.0.12...v7.0.13)

> 30 March 2021

- fixing regression that removed the ability to pass a string to anyToJson while in a browser context [`a590278`](https://github.com/TeselaGen/ve-sequence-parsers/commit/a59027822cbfd44ac3ae5fd81df94a7a59b45a56)
- Merge pull request #172 from TeselaGen/dependabot/npm_and_yarn/y18n-3.2.2 [`f2491ed`](https://github.com/TeselaGen/ve-sequence-parsers/commit/f2491edb6adbc2249111d5d49f8ffcc78bc7cad7)
- [Security] Bump y18n from 3.2.1 to 3.2.2 [`d73a5a5`](https://github.com/TeselaGen/ve-sequence-parsers/commit/d73a5a5fe0db7491b88284fc5475302079c704f2)

#### [v7.0.12](https://github.com/TeselaGen/ve-sequence-parsers/compare/v7.0.11...v7.0.12)

> 12 March 2021

- removing /test files from npm [`9bb1eaf`](https://github.com/TeselaGen/ve-sequence-parsers/commit/9bb1eaf32b5fbbff2139b23abfc0e4af20973289)

#### [v7.0.11](https://github.com/TeselaGen/ve-sequence-parsers/compare/v7.0.10...v7.0.11)

> 12 March 2021

- removing /test files from npm [`696823e`](https://github.com/TeselaGen/ve-sequence-parsers/commit/696823ea6130a6339a8c5032b04b4a286413d40e)

#### [v7.0.10](https://github.com/TeselaGen/ve-sequence-parsers/compare/v7.0.9...v7.0.10)

> 12 March 2021

- removing /test files from npm [`ea95cf5`](https://github.com/TeselaGen/ve-sequence-parsers/commit/ea95cf55edc6b8e88f113ad4128e6efa9f6cb595)

#### [v7.0.9](https://github.com/TeselaGen/ve-sequence-parsers/compare/v7.0.8...v7.0.9)

> 12 March 2021

- removing /test files from npm [`37fc1c9`](https://github.com/TeselaGen/ve-sequence-parsers/commit/37fc1c975fb3cdee75159b22639e3db5d08a70d0)

#### [v7.0.8](https://github.com/TeselaGen/ve-sequence-parsers/compare/v7.0.7...v7.0.8)

> 12 March 2021

- removing /test files from npm [`2458f0f`](https://github.com/TeselaGen/ve-sequence-parsers/commit/2458f0f0ed14705ca04b9d63c60de06f6e5174f0)

#### [v7.0.7](https://github.com/TeselaGen/ve-sequence-parsers/compare/v7.0.6...v7.0.7)

> 12 March 2021

- updating snapgene parser to pull off custom names and description [`5839422`](https://github.com/TeselaGen/ve-sequence-parsers/commit/58394225beaccb3750cf0d9255d96d4b48051daa)

#### [v7.0.6](https://github.com/TeselaGen/ve-sequence-parsers/compare/v7.0.5...v7.0.6)

> 3 March 2021

- removing waldojs as a dependency [`4ab66a8`](https://github.com/TeselaGen/ve-sequence-parsers/commit/4ab66a8937983180dbac68f8e5c89715dd070f78)
- Merge pull request #163 from TeselaGen/dependabot/npm_and_yarn/lodash-4.17.21 [`409f026`](https://github.com/TeselaGen/ve-sequence-parsers/commit/409f026dc590d35289b37a445e5eafa6664f32ee)
- [Security] Bump lodash from 4.17.15 to 4.17.21 [`fe18b24`](https://github.com/TeselaGen/ve-sequence-parsers/commit/fe18b2450537756ccf1e46590f78bac2d9fa3211)

### [v7.0.5](https://github.com/TeselaGen/ve-sequence-parsers/compare/1.0.3...v7.0.5)

> 17 February 2021

- Fixed typos concerning xxxxToJson [`#102`](https://github.com/TeselaGen/ve-sequence-parsers/pull/102)
- Fixed typos [`#101`](https://github.com/TeselaGen/ve-sequence-parsers/pull/101)
- [Security] Bump merge from 1.2.0 to 1.2.1 [`#27`](https://github.com/TeselaGen/ve-sequence-parsers/pull/27)
- [Security] Bump stringstream from 0.0.5 to 0.0.6 [`#30`](https://github.com/TeselaGen/ve-sequence-parsers/pull/30)
- [Security] Bump tar from 2.2.1 to 2.2.2 [`#31`](https://github.com/TeselaGen/ve-sequence-parsers/pull/31)
- [Security] Bump lodash from 4.17.11 to 4.17.13 [`#32`](https://github.com/TeselaGen/ve-sequence-parsers/pull/32)
- [Security] Bump fstream from 1.0.11 to 1.0.12 [`#22`](https://github.com/TeselaGen/ve-sequence-parsers/pull/22)
- [Security] Bump extend from 3.0.1 to 3.0.2 [`#21`](https://github.com/TeselaGen/ve-sequence-parsers/pull/21)
- Added gff sequence parser [`#19`](https://github.com/TeselaGen/ve-sequence-parsers/pull/19)
- Remove dot at .dna check for snapgene extension [`#18`](https://github.com/TeselaGen/ve-sequence-parsers/pull/18)
- added more GenBank feature types [`#10`](https://github.com/TeselaGen/ve-sequence-parsers/pull/10)
- Updated fasta protein validation message [`#11`](https://github.com/TeselaGen/ve-sequence-parsers/pull/11)
- not replace spaces for _ on proteins [`#3`](https://github.com/TeselaGen/ve-sequence-parsers/pull/3)
- adding a UMD build and removing es and lib from github [`b90db4f`](https://github.com/TeselaGen/ve-sequence-parsers/commit/b90db4fd27ff68279cab5a998b067780cda6a7b2)
- updating readme and adding built files [`89d3a8c`](https://github.com/TeselaGen/ve-sequence-parsers/commit/89d3a8c2969bba954e7c322bf3884654e34d687a)
- publishing new patch [`7c74ddd`](https://github.com/TeselaGen/ve-sequence-parsers/commit/7c74ddd76ee7ef2e84781fc6a48ce48286e65bef)

#### [1.0.3](https://github.com/TeselaGen/ve-sequence-parsers/compare/1.0.2...1.0.3)

> 1 March 2016

- updating package.json [`c100ace`](https://github.com/TeselaGen/ve-sequence-parsers/commit/c100ace89897de384a446673bdee62fc7887cdfa)

#### [1.0.2](https://github.com/TeselaGen/ve-sequence-parsers/compare/1.0.0...1.0.2)

> 24 February 2016

- removing try/catch that was eating errors in xml parser [`7758d09`](https://github.com/TeselaGen/ve-sequence-parsers/commit/7758d09a0165236bb877e3265f1cffb549fb2af6)

#### 1.0.0

> 23 February 2016

- updating travis [`#2`](https://github.com/TeselaGen/ve-sequence-parsers/pull/2)
- fixing tests [`#1`](https://github.com/TeselaGen/ve-sequence-parsers/pull/1)
- setting up repo [`ce75a1f`](https://github.com/TeselaGen/ve-sequence-parsers/commit/ce75a1f17ea45351d89b0616b6853d2415ab3c10)
- updating parsers to limit length of feature names [`1cfcf09`](https://github.com/TeselaGen/ve-sequence-parsers/commit/1cfcf093dc089b20a9150e760e3dc9b3baef60b7)
- updating interface to all parsers to follow: 'string, callback, [options]' style signature [`8ab1c1a`](https://github.com/TeselaGen/ve-sequence-parsers/commit/8ab1c1ad31340a98810a7b7af4c00fa17af5d404)
