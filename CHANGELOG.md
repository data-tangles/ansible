# [0.2.0](https://github.com/data-tangles/ansible/compare/v0.1.2...v0.2.0) (2024-09-14)


### Bug Fixes

* add additional telegraf config ([8798670](https://github.com/data-tangles/ansible/commit/87986708d78df751f1d9915a74e1814bf93b40a8))
* add become to node exporter install ([9469562](https://github.com/data-tangles/ansible/commit/9469562a374fc53d6fdea2c3fd5b8188eb8f9f17))
* add conditional `become` option for telegraf playbook ([e6938f7](https://github.com/data-tangles/ansible/commit/e6938f798c2460c063f3d71dcb1020663086ec73))
* add debian repositories to edgeos ([44c8d59](https://github.com/data-tangles/ansible/commit/44c8d59436eb15ae11748df5749f284cf79845ab))
* add default for network os ([846af18](https://github.com/data-tangles/ansible/commit/846af18df5c1906ea02583cf428c52d7a290b464))
* add removal ([191bf45](https://github.com/data-tangles/ansible/commit/191bf45e5cc50fa3b9d580b45b418bb0f36cdf46))
* alter apt install ([25230b4](https://github.com/data-tangles/ansible/commit/25230b47ba8593a109b874b7a96776b4ce57bd52))
* change `become` options ([8dc90dd](https://github.com/data-tangles/ansible/commit/8dc90dda0abba0cf12e9ee227b7b6ad9e25daa48))
* change error handling ([83914ba](https://github.com/data-tangles/ansible/commit/83914ba50b755778d694fa3a673dfca396a636a2))
* change github actions workflow ([db20b81](https://github.com/data-tangles/ansible/commit/db20b81c83a4c46cd8bc9c24f38d8eefa3768c4b))
* change prometheus test url path ([3952795](https://github.com/data-tangles/ansible/commit/3952795695befb57676bc346c4aab4cc5db33df9))
* change telegraf connection settings ([8c76274](https://github.com/data-tangles/ansible/commit/8c7627422650867cf8cf58392d7eedd34a4daf3e))
* change to command module to prevent apt cache ([e2cd5d0](https://github.com/data-tangles/ansible/commit/e2cd5d048552be9042c825dede47425e34812d8b))
* correct edgeos agent version ([cd8a6f5](https://github.com/data-tangles/ansible/commit/cd8a6f52b8ad835d028d35b69341b24868bb56ea))
* correct node exporter check task ([3b65718](https://github.com/data-tangles/ansible/commit/3b6571840fee2e1f7e33ae32fc9ff916406fbc98))
* correct pull request head ref ([1b6d0bd](https://github.com/data-tangles/ansible/commit/1b6d0bdb23fdadb62f09540a9e7d00502e203218))
* correct pull request ref ([402d1e3](https://github.com/data-tangles/ansible/commit/402d1e3760d9263939094ba3b6ed01430892a5ea))
* correct workflow ([44aab39](https://github.com/data-tangles/ansible/commit/44aab39bedbc472f3f36972bd43cc97c75055ca7))
* fix edgeos download method ([5be54bc](https://github.com/data-tangles/ansible/commit/5be54bcbe1c853fae468d825fe7b9e5218f1ca1e))
* fix install ([edafbc7](https://github.com/data-tangles/ansible/commit/edafbc7b1a026f7d2b28b5044bc9ea222a62a944))
* only run on pull request ([ec99fd1](https://github.com/data-tangles/ansible/commit/ec99fd1e87bc49b19032f7c0cb61157cf415afb8))
* remove additional workflow checks ([b08905a](https://github.com/data-tangles/ansible/commit/b08905a8ae6fe9a16dcda1d71205207c9d0c74fe))
* remove become requirement ([849e5f3](https://github.com/data-tangles/ansible/commit/849e5f3c474cb048abd14bf818406178ee3afb2b))
* remove deb repository addition ([0f41550](https://github.com/data-tangles/ansible/commit/0f41550ee97b023ac0a14ec3993aec71bdabf3ba))
* remove power status for edgeos ([45f1a57](https://github.com/data-tangles/ansible/commit/45f1a57ee086562f018630548e7b6ffc9d7206bd))
* remove pull request action ([97d2806](https://github.com/data-tangles/ansible/commit/97d280636177ef2523ac7a1ef3ff504894b86ec8))
* remove skip git pull from workflow ([2ae5254](https://github.com/data-tangles/ansible/commit/2ae52540462d76ceb20aa4f8be5d6f1e831387a1))
* remove telegraf removal task ([3d0ca7b](https://github.com/data-tangles/ansible/commit/3d0ca7b320f1b9a5cd79531f4c65acbb637da8f2))
* renam,e telegraf playbook ([718c486](https://github.com/data-tangles/ansible/commit/718c486de777b1fa2cc7922504c0aac8a4e34c23))
* rename roles and playbooks ([e98f54e](https://github.com/data-tangles/ansible/commit/e98f54e13c02fb481db0e5d676420547345b3c00))
* run workflow ([f7da1c0](https://github.com/data-tangles/ansible/commit/f7da1c0ea0951c367d9b88b84c86fc0093db7ae7))
* set wait time for oci backup to cater to larger disks ([ba0d7e4](https://github.com/data-tangles/ansible/commit/ba0d7e447609ddd4bfe726929cb930b8640641dd))
* Update Portainer version to fix UI Console Exec ([c213357](https://github.com/data-tangles/ansible/commit/c2133573333265de486ba7880fce6c7c47aa69b0))


### Features

* add edgeos telegraf install ([9e6f7f6](https://github.com/data-tangles/ansible/commit/9e6f7f64e3128d413dfbe8a4bd6382e966c2bb26))
* add linux node exporter install playbook ([093938f](https://github.com/data-tangles/ansible/commit/093938f9ac99d56f6eee0301d1daec5e5593c27a))
* add prometheus windows exporter role ([4af1e54](https://github.com/data-tangles/ansible/commit/4af1e541f39ec2669dd32a26319683f7c4cedf44))
* add telegraf role ([17fb537](https://github.com/data-tangles/ansible/commit/17fb537e3b044dbf729430139c82e938d5e55ed7))



## [0.1.2](https://github.com/data-tangles/ansible/compare/v0.1.1...v0.1.2) (2024-04-20)


### Bug Fixes

* change GitHub Actions Runner Docker environment variable ([3eecdd2](https://github.com/data-tangles/ansible/commit/3eecdd2ba115ff8594f03988d9d088383eb93919))



## [0.1.1](https://github.com/data-tangles/ansible/compare/v0.1.0...v0.1.1) (2024-04-20)


### Bug Fixes

* Add `USE_HOSTNAME` variable to GitHub Actions Runner playbook ([faa52d2](https://github.com/data-tangles/ansible/commit/faa52d248b09a7450e0dc4fa3b4e664cc8188db2))



# [0.1.0](https://github.com/data-tangles/ansible/compare/e9cdf676a9c9665f1c53486de2bc5b5b48a761a7...v0.1.0) (2024-04-20)


### Bug Fixes

* add checkout step ([052862d](https://github.com/data-tangles/ansible/commit/052862dab51c607d0e349dd6614d011d6e1f4c40))
* change gha playbook env variable ([47f0f8c](https://github.com/data-tangles/ansible/commit/47f0f8c2a67d2a8d87ab840264186212347e7cdf))
* change github actions runner playbook ([e9cdf67](https://github.com/data-tangles/ansible/commit/e9cdf676a9c9665f1c53486de2bc5b5b48a761a7))
* Correct GitHub Actions workflow branch reference to `main` ([0d016b0](https://github.com/data-tangles/ansible/commit/0d016b00e89f51a6f73373fe1f733355d1e9fe0c))
* remove GitHub Actions permissions ([479d325](https://github.com/data-tangles/ansible/commit/479d325900817e90d76fcc42f2091589cd81a1ca))


### Features

* various improvements to codebase ([645f668](https://github.com/data-tangles/ansible/commit/645f66859cd065e757cd3c61693787eb2fa0e926))



