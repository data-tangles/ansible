# [0.2.0](https://github.com/data-tangles/ansible/compare/v0.1.2...v0.2.0) (2025-03-29)


### Bug Fixes

* add additional telegraf config ([8798670](https://github.com/data-tangles/ansible/commit/87986708d78df751f1d9915a74e1814bf93b40a8))
* add become method and create scripts directory for loadshedding script ([c1e2b48](https://github.com/data-tangles/ansible/commit/c1e2b483c7db5f83a558a7482c2f1f130ee13bba))
* add become to node exporter install ([9469562](https://github.com/data-tangles/ansible/commit/9469562a374fc53d6fdea2c3fd5b8188eb8f9f17))
* add conditional `become` option for telegraf playbook ([e6938f7](https://github.com/data-tangles/ansible/commit/e6938f798c2460c063f3d71dcb1020663086ec73))
* add debian repositories to edgeos ([44c8d59](https://github.com/data-tangles/ansible/commit/44c8d59436eb15ae11748df5749f284cf79845ab))
* add default for network os ([846af18](https://github.com/data-tangles/ansible/commit/846af18df5c1906ea02583cf428c52d7a290b464))
* add directory creation step to playbook ([c2a5a8c](https://github.com/data-tangles/ansible/commit/c2a5a8ca49d88ce42c875d53cf3fbec2bd95b753))
* add removal ([191bf45](https://github.com/data-tangles/ansible/commit/191bf45e5cc50fa3b9d580b45b418bb0f36cdf46))
* add win_update log file ([472b80d](https://github.com/data-tangles/ansible/commit/472b80d84894a4facb032192181563b49a00c2de))
* alter apt install ([25230b4](https://github.com/data-tangles/ansible/commit/25230b47ba8593a109b874b7a96776b4ce57bd52))
* change `become` options ([8dc90dd](https://github.com/data-tangles/ansible/commit/8dc90dda0abba0cf12e9ee227b7b6ad9e25daa48))
* change error handling ([83914ba](https://github.com/data-tangles/ansible/commit/83914ba50b755778d694fa3a673dfca396a636a2))
* change github actions workflow ([db20b81](https://github.com/data-tangles/ansible/commit/db20b81c83a4c46cd8bc9c24f38d8eefa3768c4b))
* change permissions of loadshedding_checker_script to executable ([9c61c22](https://github.com/data-tangles/ansible/commit/9c61c220d118deb5ac4e3ee867cc7b62449aa797))
* change prometheus test url path ([3952795](https://github.com/data-tangles/ansible/commit/3952795695befb57676bc346c4aab4cc5db33df9))
* change telegraf connection settings ([8c76274](https://github.com/data-tangles/ansible/commit/8c7627422650867cf8cf58392d7eedd34a4daf3e))
* change to command module to prevent apt cache ([e2cd5d0](https://github.com/data-tangles/ansible/commit/e2cd5d048552be9042c825dede47425e34812d8b))
* correct edgeos agent version ([cd8a6f5](https://github.com/data-tangles/ansible/commit/cd8a6f52b8ad835d028d35b69341b24868bb56ea))
* correct node exporter check task ([3b65718](https://github.com/data-tangles/ansible/commit/3b6571840fee2e1f7e33ae32fc9ff916406fbc98))
* correct pull request head ref ([1b6d0bd](https://github.com/data-tangles/ansible/commit/1b6d0bdb23fdadb62f09540a9e7d00502e203218))
* correct pull request ref ([402d1e3](https://github.com/data-tangles/ansible/commit/402d1e3760d9263939094ba3b6ed01430892a5ea))
* correct syntax in Docker repository definition and add filename parameter ([82b3763](https://github.com/data-tangles/ansible/commit/82b3763d18ffca1cc3c5fa8d63e5e63f48ecc663))
* correct workflow ([44aab39](https://github.com/data-tangles/ansible/commit/44aab39bedbc472f3f36972bd43cc97c75055ca7))
* enhance Docker installation tasks with architecture-specific variables and GPG key management ([ee479a8](https://github.com/data-tangles/ansible/commit/ee479a827256d9b063e686d788252471861d1cb4))
* fix edgeos download method ([5be54bc](https://github.com/data-tangles/ansible/commit/5be54bcbe1c853fae468d825fe7b9e5218f1ca1e))
* fix install ([edafbc7](https://github.com/data-tangles/ansible/commit/edafbc7b1a026f7d2b28b5044bc9ea222a62a944))
* only run on pull request ([ec99fd1](https://github.com/data-tangles/ansible/commit/ec99fd1e87bc49b19032f7c0cb61157cf415afb8))
* remove additional workflow checks ([b08905a](https://github.com/data-tangles/ansible/commit/b08905a8ae6fe9a16dcda1d71205207c9d0c74fe))
* remove become for loadshedding script playbook ([1e2e4cf](https://github.com/data-tangles/ansible/commit/1e2e4cfdb20de9d4c44a24a0f0e600c4a88af434))
* remove become method ([dab29de](https://github.com/data-tangles/ansible/commit/dab29de10f1e86e05d1216bb67f6b93f29f4a9f2))
* remove become requirement ([849e5f3](https://github.com/data-tangles/ansible/commit/849e5f3c474cb048abd14bf818406178ee3afb2b))
* remove deb repository addition ([0f41550](https://github.com/data-tangles/ansible/commit/0f41550ee97b023ac0a14ec3993aec71bdabf3ba))
* remove power status for edgeos ([45f1a57](https://github.com/data-tangles/ansible/commit/45f1a57ee086562f018630548e7b6ffc9d7206bd))
* remove pull request action ([97d2806](https://github.com/data-tangles/ansible/commit/97d280636177ef2523ac7a1ef3ff504894b86ec8))
* remove pull_request trigger from main workflow and adjust changelog action condition ([520daa1](https://github.com/data-tangles/ansible/commit/520daa1aaf59e1d9f16e07e0bed08006e642390d))
* remove skip git pull from workflow ([2ae5254](https://github.com/data-tangles/ansible/commit/2ae52540462d76ceb20aa4f8be5d6f1e831387a1))
* remove telegraf removal task ([3d0ca7b](https://github.com/data-tangles/ansible/commit/3d0ca7b320f1b9a5cd79531f4c65acbb637da8f2))
* remove unnecessary state parameter from Docker GPG key installation task ([01e668d](https://github.com/data-tangles/ansible/commit/01e668dce3328d99246fbabdbbc66bf37bd46a95))
* renam,e telegraf playbook ([718c486](https://github.com/data-tangles/ansible/commit/718c486de777b1fa2cc7922504c0aac8a4e34c23))
* rename roles and playbooks ([e98f54e](https://github.com/data-tangles/ansible/commit/e98f54e13c02fb481db0e5d676420547345b3c00))
* run workflow ([f7da1c0](https://github.com/data-tangles/ansible/commit/f7da1c0ea0951c367d9b88b84c86fc0093db7ae7))
* set wait time for oci backup to cater to larger disks ([ba0d7e4](https://github.com/data-tangles/ansible/commit/ba0d7e447609ddd4bfe726929cb930b8640641dd))
* update architecture variable for arm64 to armhf ([a5fcb02](https://github.com/data-tangles/ansible/commit/a5fcb02b03d6c4882854b2b69ef7048700962717))
* update architecture variable for armv7l in docker_install task and add pull_request trigger to workflow ([2394820](https://github.com/data-tangles/ansible/commit/23948203aec15acdf39f77179227b7d88762dc68))
* update Discord notification message to include hostname in loadshedding_checker_script ([068d399](https://github.com/data-tangles/ansible/commit/068d399d21052d53bef8bf3fa5cee61462765852))
* update Docker installation tasks to use dynamic repository URL and include additional packages ([8ecd388](https://github.com/data-tangles/ansible/commit/8ecd3888c29d2ca58b8f6641046602f91b41c58d))
* update loadshedding script paths and remove unnecessary directory creation ([926b46e](https://github.com/data-tangles/ansible/commit/926b46ef006003cbbc26860241b28473bb9fabab))
* update playbook host variable from HOSTS to nodes ([38cae77](https://github.com/data-tangles/ansible/commit/38cae77aa8952e96b9373ebe11198f7dbdc116d9))
* Update Portainer version to fix UI Console Exec ([c213357](https://github.com/data-tangles/ansible/commit/c2133573333265de486ba7880fce6c7c47aa69b0))
* update shutdown command path in cron job for loadshedding script ([f1ba73e](https://github.com/data-tangles/ansible/commit/f1ba73e021c9cb197667ebf23ec74ce50cc820e9))
* update task module references to use fully qualified names ([adab3da](https://github.com/data-tangles/ansible/commit/adab3da27e223ad09dd6acc570eabf1f7fe82a2c))


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



